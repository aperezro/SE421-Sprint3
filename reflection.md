# Reflection — Complexity Lab

For this learning sprint, I developed an interactive browser visualization that compares logarithmic, linear, quadratic, and exponential algorithmic growth. My goal was to make algorithmic complexity feel concrete rather than just memorizing Big-O notation. The app lets users adjust an input-size slider, switch algorithms, and immediately see the resulting operation counts and comparison bars.

The most useful insight was how differently algorithms respond to the same increase in input size. For example, doubling a linear input roughly doubles its work, while adding only a few levels to exponential recursion can multiply its work dramatically. This helped me connect complexity analysis to security: an algorithmic-complexity vulnerability occurs when an input causes unexpectedly large computational work, potentially exhausting a service's resources.

I used an AI-assisted workflow to plan the interface, generate an initial HTML/CSS/JavaScript implementation, and draft explanations of the complexity classes. I then reviewed the formulas, interaction behavior, and educational wording to ensure the visualization used simulated operation counts rather than triggering actual resource-intensive behavior. Keeping everything in one HTML file made the app easy to run and share.

This project reinforced the importance of choosing efficient algorithms and thinking about worst-case input behavior when designing secure software. It also showed me how an interactive visualization can communicate an abstract security concept more clearly than a static definition.
