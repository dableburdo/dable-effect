# dable-effect
Dable effect is module based frontend framework. synchronize height of target component and height of effect component this effect resizes height of a target component when the height of the target component changed.

# Install
```
npm install dable-effect
```

# Sample
```html
<setting>
    <tag load="dable-comp-text">Text</tag>
    <tag load="dable-comp-frame">Frame</tag>
    <tag load="dable-effect-synchei">SyncHei</tag>
</setting>
<Frame name=frm size=(3rem,1rem)>
    <Text effect=SynHei:(@frm,"-0.3rem")>Sync Height</Text>
</Frame>
```
