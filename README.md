# philosophers

This project was made to make us learn about threads, and how they interact with mutex.

The goal was to monitor a group of P philosophers(threads) that needs to eat every X ms, or else they die and the simulation ends.

The cycle goes like this: -Take a fork, take a second fork, eat Y ms, sleep Z ms, then think as long as no fork is available.

A philosopher cannot eat without two forks(mutex) and obviously a taken fork cannot be used by it's owner.

An optional variable could be added (N), which represent the number of time each philosopher had to eat before ending the simulation.

./philo P X Y Z (N);

![image](https://user-images.githubusercontent.com/100093373/230636259-b4ca6410-39fb-4742-b183-779e06503c40.png)
