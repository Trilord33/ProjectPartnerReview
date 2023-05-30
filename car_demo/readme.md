# Basic Car Model

to run:
```
cargo run --release
```

Systems include
- suspension: wheels move up and down relative to the chassis
- tires: forces are applied to the wheels when the tires slip
- driving wheels: torque is applied to the wheels to maintain speed
- steering: mostly turns left, but oscillates a bit

Files
- build: builds the car model
- physics: defines the physics of the car systems

## TODO
- organize the code better
- run physics faster than rendering
- improve the tire model
- so much more...

