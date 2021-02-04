# Dynamics version of Association Rules Learning(ARL)


### What is the Association Rules Learning?

It is a rule-based machine learning technique used to find patterns (relationships, structures) in the data.

Association analysis applications are among the most common applications in data science. It will also coincide as Recommendation Systems.

These applications may have come up in the following ways, such as "bought this product that bought that product" or "those who viewed that ad also looked at these ads" or "we created a playlist for you" or "recommended video for the next video".

These scenarios are the most frequently encountered scenarios within the scope of e-commerce data science data mining studies.

In Turkey and the world's largest e-commerce companies spotify, amazon, it uses many platforms like netflix recommendation systems can know a little more closely.
So what does this association analysis summarize?
Apriori Algorithm

It is the most used method in this field.

Association rule analysis is carried out by examining some metrics:

    Support Support(X, Y) = Freq(X,Y)/N

      X: Product
      Y: Product
      N: Total Shopping

    Confidence

      Confidence (X, Y) = Freq (X, Y) / Freq (X)

    Lift (The purchase of one product increases the level of purchase of the other.)

      Lift = Support (X, Y) / (Support (X) * Support (Y))
