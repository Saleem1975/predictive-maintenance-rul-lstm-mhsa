# Limitations and Future Work

## Limitations

### 1. Simulated case study

The case study uses simulated capacitor degradation trajectories designed to mimic realistic degradation behavior. Real industrial deployment would require validation on real equipment data.

### 2. Limited training data challenge

Although the proposed model is robust under limited complete run-to-failure trajectories, performance still depends on the diversity and representativeness of training data.

### 3. Equipment-specific behavior

The model was applied to aluminium electrolytic capacitors. Other equipment types may require different input signals, preprocessing, and validation.

### 4. Implementation requirements

Deployment would require integration with sensor systems, data pipelines, maintenance workflows, and model monitoring.

## Future work

Future work can include:

- Testing the approach on real industrial sensor datasets
- Extending the model to other equipment classes
- Developing uncertainty-aware RUL estimates
- Integrating the model into maintenance dashboards
- Combining data-driven models with physics-based degradation knowledge
- Applying the method to production lines and Industry 4.0 applications
