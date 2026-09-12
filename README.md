**Topic: honeybee Toxicity Ai**
**The Problem**
Honey bees pollinate one third of global food crops, but pesticides are killing them. Testing every new pesticide on live bees takes weeks and costs $10,000 to $50,000 per compound.
**The Solution**
A machine learning model that takes a molecule's SMILES string and predicts in milliseconds whether it is toxic (1) or non-toxic (0) to honey bees.
**How It Works**
Data Merged 3 public databases (BPDB, ECOTOX, PPDB)   925 unique molecules

Features   3,000+ chemical features (fingerprints, descriptors, toxicophores, 3D, graph)

Model   XGBoost classifier, ROC-AUC ≈ 0.85

Explainability  SHAP shows which chemical groups cause toxicity
**Why It Matters**
Honey bees pollinate approximately one third of the world's food crops, making them indispensable to global food security and agricultural economies worth hundreds of billions of dollars annually. Yet their populations continue to decline, with pesticide exposure identified as a leading cause. Current regulatory toxicity testing, however, is slow, expensive, and resource-intensive requiring live bee colonies, weeks of testing per compound, and costs of $10,000 to $50,000 per molecule. 
**This creates a critical bottleneck:** thousands of new agrochemicals are synthesized each year, but only a small fraction can ever be tested. This project addresses that gap directly. By predicting honey bee toxicity from molecular structure alone, it enables agrochemical companies to screen thousands of candidate compounds computationally before committing to synthesis or laboratory testing, allows regulators to prioritize their review queues by predicted risk, and gives researchers a reproducible scientific baseline for pollinator toxicology. Beyond efficiency, the model is interpretable  it identifies which chemical groups drive toxicity, offering actionable guidance for designing safer molecules. Ultimately, this work contributes to a larger goal: protecting the pollinators that sustain global agriculture, reducing unnecessary animal testing, and accelerating the development of environmentally responsible agrochemicals. It is a concrete example of how artificial intelligence, applied thoughtfully to scientific problems, can translate into measurable real world impact.
