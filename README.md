# STANFORD-RL
### __QUESTIONS?__
---
<ol style="list-style-type:lower-roman;">
    <li>
        David Silver teaches that rewards are given upon leaving a state in his YouTube lectures. The P[state][action] multimap assigns different rewards to each action available at a state which implies that the reward is coming for the next state. This seems to be equivalent before, but it slightly modifies the look of the calculation. Which style is more common?
    </li>
</ol>

### __TECHNICAL PARTICULARS__
---

#### __enable recording of the episodes__
<ol style="list-style-type:lower-roman;">
    <li>
        ./script.sh "python ./vi_and_pi.py"
    </li>
</ol>

#### normal run with terminal based output
<ol style="list-style-type:lower-roman;">
    <li>
        python vi_and_pi.py -t
    </li>
</ol>

#### sometimes needed to cleanup video driver between episodes
<ol style="list-style-type:lower-roman;">
    <li>
        rm /tmp/.X1
    </li>
    <li>
        rm /tmp/.X11-unix/X1
    </li>
</ol>

#### frozen lakes does not require the wrapper_env
<ol style="list-style-type:lower-roman;">
    <li>
        it is a terminal based ascii environment
    </li>
</ol>
