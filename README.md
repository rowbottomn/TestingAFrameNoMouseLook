# Flying Controls and Pointer Lock Example

`   <a-entity id="rig"
          movement-controls="fly: true; easingY: 30"
          position="0 0 0">
  <a-entity camera
            position="0 1.6 0"
            look-controls="pointerLockEnabled: true"></a-entity>
</a-entity>`

The first rig had the movement controls to allow flying.
The camera has look controls locked to the mousedirection