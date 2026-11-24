# Laundry robot (Hamoksha)

A home robot built step by step in a home workshop. It started as a fixed arm in the laundry room that opens the washing machine door, and grew into a mobile robot called Hamoksha with arms, a vertical lift, a depth camera, voice and a kids' story mode.

This repository is the build-it-yourself guide. Each phase has its own folder with:

- what we built and why
- the bill of materials (BOM): component names and photos
- build and wiring notes, and the problems we hit

> Nothing here is a purchase recommendation. Components are listed by name only.

## Acknowledgments

Hamoksha is built on the XLeRobot project (https://xlerobot.readthedocs.io/en/latest/index.html), an open-source household dual-arm mobile robot released under the Apache 2.0 license. The two arms (SO-ARM101), the wheeled base parts and the camera mount parts came from that project and its kit. The kit had no depth camera, so the Intel RealSense D435 was added separately. XLeRobot itself builds on LeRobot, SO-100/SO-101, LeKiwi and Bambot. Please read the XLeRobot documentation alongside this guide, and respect its license for any of its files you reuse.

## Print files

Ready-to-print STL files for the parts we designed are in the [stl](stl/README.md) folder. The CAD scripts that generate them are not published.

## What is not in this repository

The robot's own software and the CAD scripts that generate the printed parts live in a separate private repository. This guide covers what to buy, how the parts fit together, the wiring notes and the problems we hit and fixed. Speakers and microphones are generic: any USB speaker and USB microphone work.

## Phases

| Phase | Topic | Folder |
|---|---|---|
| 1 | Laundry door opener | [docs/phase-01-laundry-door-opener](docs/phase-01-laundry-door-opener/README.md) |
| 2 | Robot kit and Jetson setup | [docs/phase-02-robot-kit-and-jetson-setup](docs/phase-02-robot-kit-and-jetson-setup/README.md) |
| 3 | Depth camera and room mapping | [docs/phase-03-depth-camera-and-room-mapping](docs/phase-03-depth-camera-and-room-mapping/README.md) |
| 4 | Arms, servos and grasping | [docs/phase-04-arms-servos-and-grasping](docs/phase-04-arms-servos-and-grasping/README.md) |
| 5 | Base frame and vertical lift | [docs/phase-05-base-frame-and-vertical-lift](docs/phase-05-base-frame-and-vertical-lift/README.md) |
| 6 | Safe driving and navigation | [docs/phase-06-safe-driving-and-navigation](docs/phase-06-safe-driving-and-navigation/README.md) |
| 7 | Voice, storytelling and kids | [docs/phase-07-voice-storytelling-and-kids](docs/phase-07-voice-storytelling-and-kids/README.md) |
| 8 | Body design, arms and screen | [docs/phase-08-body-design-arms-and-screen](docs/phase-08-body-design-arms-and-screen/README.md) |
| 9 | Lift debugging and electronics box | [docs/phase-09-lift-debugging-and-electronics-box](docs/phase-09-lift-debugging-and-electronics-box/README.md) |
| 10 | Mecanum wheel drive | [docs/phase-10-mecanum-wheel-drive](docs/phase-10-mecanum-wheel-drive/README.md) |

## Working rules we follow

- No CAD from guessed dimensions. Measure with a caliper, or take the number from the part's drawing first.
- One part per print job.
- Verify a part's listing and drawing before ordering.

## License

Apache 2.0, see [LICENSE](LICENSE).

## How each phase page is built

Every phase folder has a `README.md` with the same sections: goal, bill of materials (names and photos only), build notes, problems and fixes, status, wiring notes. Photos are in the `images` folder next to it.
