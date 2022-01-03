# Federate AI for Real-World Business Scenarios

Comments from my reading.

## Preface

- ML (and AI) have a huge potential to improve business operations and we only scratched the surface
- AI captures patterns that are inherit in the data and represent those patterns in a AI Model
- Access to data large volumes of high quality data is essential to build good AI models
- Two main steps: learning and inference
- Insufficient training data leads to poor models ( not good enough to be useful)
- Data is not easily accessible: regulations constrain how data can be shared

### Which constraints avoids data to be used?

- Privacy and Security
- Different locations
- Inconsistent formats
- Moving data is very expensive and/or takes lots of time
- Limited network connectivity
- Not very good data collection process

### Problem

Creating AI models from data that is stores in may different locations: requires federated learning approach.

- Local models are created in each site and combined later into a single model
- This can also be used not only in the learning step but also in the inference step: federated inference

### Secondary problem

AI/ML has to be decoupled from the statistics and programming and cast in terms which make sense to the business developer and technical architect:
 
- Focus on real-world system building aspects
- Model-building exercise from the perspective of a non-statistician and non-programmer
- AI/ML models from the perspective of a business developer or technical architect
- Federated learning should be understood in a business friendly perspective
- Focus of use AI in business settings and problems and might not be highly relevant in the academic space

### Performance and effectiveness

- It al depends on the nature of the data used to train and real data input into the inference step
- Avoided the temptation to show data driven results to compare different approaches
- Tried to identify qualitative reasons and conditions under which some approaches should work better than the others


## Chapter 1


### Business Operation Model


### The learn -> infer -> act cycle

