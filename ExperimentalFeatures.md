# Experimental features #

To enable experimental features set property loadExperimentalFeatures on true in config.xml (or $HOME/.otroslogviewer/config.xml). Configuration should looks similar to this:

```
<?xml version="1.0" encoding="UTF-8" standalone="no"?>
<configuration>
  <gui>
    <searchMode>QUERY</searchMode>
    <markColor>Pink</markColor>
    <markFound>true</markFound>
    <showTipOfTheDay>true</showTipOfTheDay>
    <state>0</state>
    <location>
      <x>136</x>
      <y>132</y>
    </location>
    <width>1270</width>
    <height>655</height>
  </gui>
  <loadExperimentalFeatures>true</loadExperimentalFeatures>
</configuration>
```

New menu `Experimental` will be available. This menu contains experimental features, which can be not working as design yet.