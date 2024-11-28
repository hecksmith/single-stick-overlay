# single-stick-overlay

A simple controller visualisation to show raw positional values for either right or left analog sticks.

Intended to be used as an overlay, e.g. when using OBS to screen-record.

## Try It

Default right-stick setup. It should detect your first active controller:

https://hecksmith.github.io/single-stick-overlay

## Configuration

To display the left stick, instead of the default of right, set `stick=left` as a URL parameter, e.g.

> https://hecksmith.github.io/single-stick-overlay/?stick=left

To show both sticks at once, set `stick=both`, e.g.

> https://hecksmith.github.io/single-stick-overlay/?stick=both

To set your deadzone (so that values below your deadzone are not displayed), set `deadzone` in the URL:

> Set a 5% deadzone:  
> https://hecksmith.github.io/single-stick-overlay/?deadzone=0.05

To combine parameters, separate them with `&`. For example, to set stick to **left** and deadzone to **5%**:

> https://hecksmith.github.io/single-stick-overlay/?stick=left&deadzone=0.05

## Contributing

The project is intentionally simple and **done**, so it is **closed to contribution**. But fork away :)

## License

MIT
