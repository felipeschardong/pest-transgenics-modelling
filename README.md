# Pest Transgenics Modelling
 
 ## Spatial distribution of genotypes over time for different refuge configurations. Considering 22% refuge in the around configuration and 23% in the other three configurations.


| Around Refuge | Block Refuge |
|------------------|-------------------|
| ![Animação torno](animations/animation_around.gif) | ![Animação bloco](animations/animation_block.gif) |

| Stripe Refuge | Random Refuge |
|------------------|-------------------|
| ![Animação faixas](animations/animation_stripe.gif) | ![Animação aleatório](animations/animation_random.gif) |

## About the Simulations

Each script under the [`codes/`](codes/) folder corresponds to a different aspect of the project.

The following scripts focus on spatial simulations with genotype dynamics:

- [`movement_reaction_around_configuration`](codes/movement_reaction_around_configuration)  
- [`movement_reaction_block_configuration`](codes/movement_reaction_block_configuration)  
- [`movement_reaction_stripes_configuration`](codes/movement_reaction_stripes_configuration)  
- [`movement_reaction_random_configuration`](codes/movement_reaction_random_configuration)  

Each of these scripts is organized into **three stages**:

### 1. Genotype Frequency Plots  
Plots showing the evolution of genotype frequencies over generations for the corresponding refuge configuration.

### 2. Spatial Distribution Snapshots  
Visualizations of the spatial arrangement of genotypes at a selected generation.

### 3. Animations  
Animations displaying the spatial dynamics over 50 generations.

---

Other scripts in the repository explore complementary aspects:

- [`resistant_allele_frequency_critical_time`](codes/resistant_allele_frequency_critical_time)  
  Time for the resistant allele to reach 50% frequency.

- [`stability_regions`](codes/stability_regions)  
  Parameter space analysis identifying stability regions.

- [`cobwebbing-method`](codes/cobwebbing-method)  
  Cobwebbing methods for phase-space visualization.

- [`general_refuge_configurations_comparision`](codes/general_refuge_configurations_comparision)  
  General comparisons between refuge configurations.
