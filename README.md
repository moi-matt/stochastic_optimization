# stochastic_optimization

Pour plus de clarté dans le script principal main.ipynb, les méthodes ont été divisées en plusieurs fichiers.


pretraitement.ipynb : pré-traitement des graphs
    -> liste_cycles
    -> pre_traitement

determinist_MIP.ipynb : MIP utilisant la probabilité comme donnée déterministe
    -> edges_MIP
    -> proba_cycle

deterministic_MIP

plot.ipynb : affichage des graphs
    -> plot_optimized_16edges
    -> plot_cycle16edges

Lshaped.ipynb : méthode en L pour résoudre le problème
    -> proba_test
    -> relaxed_sub
    -> Lshaped_relax
