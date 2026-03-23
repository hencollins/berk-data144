## 🛸UFOs in the continental US
A capstone project for Data 144 - "Data Mining and Analytics" @ UC Berkeley. Wanted to explore machine learning applications in UFO sightings (they did ask us to be creative). Turns out UFO sightings are hard to predict and categorize...

# Tools and tech
 - <Python>
 - <pandas>
 - <scikit-learn> for MLP classification and clustering
 - <matplotlib> for neural net and cluster visualizations
 - <Canva> for presentation slides

# The project
This project was kind of a failure, BUT failure is when we learn the most! I started with some EDA and preprocessing. Cleaning the data in itself was a major accomplishment (it was the least organized data I think I've ever seen) but I ended up making something usable. During preprocessing, I also made a grid over the continental US to subdivide the country by regions instead of states. I then used scikit-learn to do an MLP classification of the probability of a UFO being spotted in one of those regions based on it's characteristics, what time it came into Earth's orbit, etc. I trained a few neural networks to perform this classification task, but landed on an <adam> solver and <1000> training iterations (not too computationally expensive), resulting in <10%> accuracy (REALLY bad I KNOW, but these are UFOs, c'mon...)

# Files
- <UFO-nn> contains preprocessing and neural network training
- <UFO-clustering> contains preprocessing and clustering visualizations
