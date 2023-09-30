# Death_Circle
This is a problem also known as The Josephus Problem

Scenerio:
N prisoners are to be put to death, except for one, who will be set free. The method to determine who will be set free is as follows: 
A gun is given to prisoner 1, and he has to shoot dead the prisonerto his left. He then passes the gun to the next prisoner (alive) on his left, who, in turn will shoot the prisoner on his left, and pass the gun to the next prisoner on his left, and so on.

For example:
If N = 5 prisoners are standing in a circle (call them prisoner 1, 2, 3, etc).
- 1 shoots 2, and passes the gun to 3.
- 3 shoots 4, and passes the gun to 5.
- 5 shoots 1, and passes the gun to 3.
- 3 shoots 5, and 3 is set free as he is the last one left.

Question to Answer:
Who is set free if N = 100?

I used python to answer the above question.
where N = number of prisoners
K - 1 is number of person that are skipped
And Kth person is killed.
