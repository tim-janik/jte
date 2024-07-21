# Juce + Tracktion-Engine

Squash forked from JUCE and tracktion_engine:

```sh
git init -b trunk
git commit --allow-empty -m '·'
git subtree add --prefix juce-framework --squash https://github.com/juce-framework/JUCE.git 7.0.12
git subtree add --prefix tracktion-engine --squash https://github.com/Tracktion/tracktion_engine.git v3.0
git subtree pull --prefix tracktion-engine --squash https://github.com/Tracktion/tracktion_engine.git master
```
