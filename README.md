# Sputnik

A quick game/story generator based on NoBoilerPlate's Video 'Building a space station in Rust (Simple Rust patterns)'

Build the project with Cargo and run the executable located in ./target/release, you can download and install the entire Rust/Cargo buildchain here - <https://www.rust-lang.org/tools/install>

```bash
cargo build --release
```

View the full video here - <https://www.youtube.com/watch?v=7GzQArrek7A>

## Example Playthrough

```text
3 UNTIL FINAL TRANSMISSION
> Enter your log: Why is there a 3 day counter
> MENU STATUS
[src\main.rs:78] &self = Station {
    name: StenSat,
    version: 57,
    sections: [
        Section {
            name: Galley,
            active: true,
        },
        Section {
            name: NuclearGenerator,
            active: false,
        },
        Section {
            name: AstroScience,
            active: false,
        },
        Section {
            name: Sleeping,
            active: false,
        },
        Section {
            name: Solar,
            active: false,
        },
        Section {
            name: Antenna,
            active: true,
        },
        Section {
            name: Transponder,
            active: true,
        },
        Section {
            name: Sleeping,
            active: false,
        },
        Section {
            name: Solar,
            active: false,
        },
        Section {
            name: Solar,
            active: false,
        },
    ],
}
3 UNTIL FINAL TRANSMISSION
> Enter your log: Both solar arrays are not functionional
> MENU NEW DAY
(sections OK)
> MENU REPAIR
> MENU Solar
4 UNTIL FINAL TRANSMISSION
> Enter your log: That seems to have bought me an extra day
> MENU NEW DAY
(Section-FAILURE Galley)
> MENU SCIENCE
> MENU Solar
(sections OK)
3 UNTIL FINAL TRANSMISSION
> Enter your log: That experiment went well
> MENU NEW DAY
(sections OK)
> MENU REPAIR
> MENU Galley
4 UNTIL FINAL TRANSMISSION
> Enter your log: Repaired the galley today
> MENU NEW DAY
(sections OK)
> MENU REPAIR
> MENU NuclearGenerator
5 UNTIL FINAL TRANSMISSION
> Enter your log: There is no hope
> MENU POWERDOWN
[src\main.rs:138] station_log = [
    "Why is there a 3 day counter",
    "Both solar arrays are not functionional ",
    "That seems to have bought me an extra day",
    "That experiment went well ",
    "Repaired the galley today",
    "There is no hope",
]
```
