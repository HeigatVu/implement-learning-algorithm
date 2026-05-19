# Graph Report - implment-algorithm  (2026-05-20)

## Corpus Check
- Corpus is ~46,100 words - fits in a single context window. You may not need a graph.

## Summary
- 46 nodes · 37 edges · 13 communities (8 shown, 5 thin omitted)
- Extraction: 100% EXTRACTED · 0% INFERRED · 0% AMBIGUOUS
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- [[_COMMUNITY_Petal Length = 0.9|Petal Length <= 0.9]]
- [[_COMMUNITY_Experience ≤ 6.0|Experience ≤ 6.0]]
- [[_COMMUNITY_344a2072-9703-4f88-aa63-e52969e996b5.json|344a2072-9703-4f88-aa63-e52969e996b5.json]]
- [[_COMMUNITY_Leaf Class 0|Leaf: Class 0]]
- [[_COMMUNITY_Experience ≤ 4.75|Experience ≤ 4.75]]
- [[_COMMUNITY_test_random_rule_sydney_opera_house_harbour|test_random_rule_sydney_opera_house_harbour]]
- [[_COMMUNITY_TSP Distance Matrix|TSP Distance Matrix]]
- [[_COMMUNITY_test_random_rule_out_plot|test_random_rule_out_plot]]
- [[_COMMUNITY_advanced_accuracy_recall_before_after_pruning_plot_accuracy_comparison|advanced_accuracy_recall_before_after_pruning_plot_accuracy_comparison]]
- [[_COMMUNITY_advanced_accuracy_recall_before_after_pruning_plot_recall_comparison|advanced_accuracy_recall_before_after_pruning_plot_recall_comparison]]
- [[_COMMUNITY_advanced_accuracy_recall_before_after_pruning_plot_max_depth|advanced_accuracy_recall_before_after_pruning_plot_max_depth]]
- [[_COMMUNITY_advanced_accuracy_recall_before_after_pruning_plot_pruning_effect|advanced_accuracy_recall_before_after_pruning_plot_pruning_effect]]
- [[_COMMUNITY_advanced_accuracy_recall_before_after_pruning_plot_overfitting_reduction|advanced_accuracy_recall_before_after_pruning_plot_overfitting_reduction]]

## God Nodes (most connected - your core abstractions)
1. `Petal Length <= 0.9` - 4 edges
2. `projectResources` - 2 edges
3. `Decision Tree (Iris)` - 2 edges
4. `resources` - 1 edges
5. `Class 0` - 1 edges
6. `Class 1` - 1 edges

## Surprising Connections (you probably didn't know these)
- `Split on Petal_Length` --splits_to--> `Leaf: Class 0`  [EXTRACTED]
   →   _Bridges community 0 → community 3_
- `Experience ≤ 4.75` ----> `Experience ≤ 6.0`  [EXTRACTED]
   →   _Bridges community 4 → community 1_

## Communities (13 total, 5 thin omitted)

### Community 0 - "Petal Length <= 0.9"
Cohesion: 0.29
Nodes (6): Split on Petal_Length, Iris Decision Tree 0, Class 0, Class 1, Petal Length <= 0.9, Decision Tree (Iris)

### Community 1 - "Experience ≤ 6.0"
Cohesion: 0.29
Nodes (7): Salary = 40.00, Salary = 65.00, Salary = 85.00, Experience ≤ 5.25, Salary = 83.00, Salary = 91.00, Experience ≤ 6.0

### Community 2 - "344a2072-9703-4f88-aa63-e52969e996b5.json"
Cohesion: 0.40
Nodes (4): id, name, projectResources, resources

### Community 3 - "Leaf: Class 0"
Cohesion: 0.50
Nodes (5): Leaf: Class 0, iris_2.svg, Class 0, Class 1, Decision: Petal_width <= 0.8

### Community 4 - "Experience ≤ 4.75"
Cohesion: 0.40
Nodes (5): Salary = 62.00, Salary = 55.00, Experience ≤ 4.75, Experience ≤ 3.75, Salary Prediction Decision Tree

### Community 5 - "test_random_rule_sydney_opera_house_harbour"
Cohesion: 0.50
Nodes (5): test_random_rule_sydney_opera_house_ferries, test_random_rule_sydney_opera_house_file, test_random_rule_sydney_opera_house_harbour, test_random_rule_sydney_opera_house_landmark, test_random_rule_sydney_opera_house_skyline

### Community 6 - "TSP Distance Matrix"
Cohesion: 0.50
Nodes (4): Project Configuration, Genetic Algorithm, TSP Distance Matrix, TSP Routing

### Community 7 - "test_random_rule_out_plot"
Cohesion: 0.67
Nodes (3): test_random_rule_out_distribution, test_random_rule_out_file, test_random_rule_out_plot

## Knowledge Gaps
- **5 isolated node(s):** `id`, `name`, `resources`, `Class 0`, `Class 1`
  These have ≤1 connection - possible missing edges or undocumented components.
- **5 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **What connects `id`, `name`, `resources` to the rest of the system?**
  _5 weakly-connected nodes found - possible documentation gaps or missing edges._