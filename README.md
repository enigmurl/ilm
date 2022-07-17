# Inductive Language Model

For now, this project is delayed. However, the underlying idea is that instead of training solely use SGD (or its relatives), there is a SGD seed stage that creates a decent language model. In the process, we not only teach it English, but *how to learn*. From here, when the ILM interacts with new english text, it can learn incredibly right on the spot (instead of having to go through the slow process of calculus).

For motivation, think about how a child learning English takes a long time to learn (this corresponds to the backpropagation stage). However, once it knows English, it's easy to expand on that knowledge because he or she can convert language instructions directly into action (this corresponds to the second and latter stages). From there, the progress is essentially exponential.
