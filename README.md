# Naive Bayes Model

When we were young we have all come across a chapter in our Maths textbooks called 'Probability'. We have come across questions like "What would be the probability of getting a 'Queen' after 'King', if we draw 2 random consecutive cards from a deck of 52 cards?" These types of question came under a topic called 'Conditional Probability'. Conditional Probability forms the base of Naive Bayes Model. To put the above example into formula:

𝑃(𝑄𝑢𝑒𝑒𝑛 𝐴𝑛𝑑 𝐾𝑖𝑛𝑔) = 𝑃(𝑄𝑢𝑒𝑒𝑛) ∗ 𝑃(𝐾𝑖𝑛𝑔|𝑄𝑢𝑒𝑒𝑛)
 
where,<br>
𝑃(𝑄𝑢𝑒𝑒𝑛 𝐴𝑛𝑑 𝐾𝑖𝑛𝑔) is the Probability of getting Queen and King on two consecutive draws<br>
𝑃(𝑄𝑢𝑒𝑒𝑛) is the Probability of getting a Queen<br>
𝑃(𝐾𝑖𝑛𝑔|𝑄𝑢𝑒𝑒𝑛) is the Probability of getting a King, given we have already drawn a card that was a Queen

To build this model I will be using National Basketball Association (NBA) dataset. I will try to predict whether a player will have a career that will last more than five years based on the data I have. There are different types of Naive Bayes Models. Here I will use a Gaussian Naive Bayes Model to make my predictions.
