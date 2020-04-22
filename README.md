# STANFORD-RL
### __QUESTIONS?__
---
<ol style="list-style-type:lower-roman;">
    <li>
        David Silver teaches that rewards are given upon leaving a state in his YouTube lectures. The P[state][action] multimap assigns different rewards to each action available at a state which implies that the reward is coming for the next state. This seems to be equivalent before, but it slightly modifies the look of the calculation. Which style is more common?
    </li>
    <li>
        My implementation of policy iteration takes one action after it reaches the terminal state. Previously, I thought that this was expected given the D.Silver method from Q1 above. It really just happened intuitively  based on how this particular assignment was designed and I wanted to note it here just in case it turns out to important later.
    </li>
</ol>


### __TECHNICAL PARTICULARS__
---
<ul>
    <li>enable recording of the episodes
        <ol style="list-style-type:lower-roman;">
            <li>
                ./script.sh "python ./vi_and_pi.py"
            </li>
        </ol>
    </li>
    <li>normal run with terminal based output
        <ol style="list-style-type:lower-roman;">
            <li>
                python vi_and_pi.py -t
            </li>
        </ol>
    </li>
    <li>sometimes needed to cleanup video driver between episodes
        <ol style="list-style-type:lower-roman;">
            <li>
                rm /tmp/.X1
            </li>
            <li>
                rm /tmp/.X11-unix/X1
            </li>
        </ol>
    </li>
    <li>frozen lakes does not require the wrapper_env
        <ol style="list-style-type:lower-roman;">
            <li>
                it is a terminal based ascii environment
            </li>
        </ol>
    </li>
</ul>
