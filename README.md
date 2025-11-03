<p align="center">
  <img src="_assets/path-planning.png" width="175">
</p>

# lozoya-path-planning

[![Buy Me A Coffee](https://img.shields.io/badge/Donate-Buy%20Me%20A%20Coffee-FFDD00?logo=buymeacoffee&logoColor=white)](https://www.buymeacoffee.com/clozoya172b)
[![Patreon](https://img.shields.io/badge/Support-Patreon-051D34?logo=patreon&logoColor=white)](https://www.patreon.com/lozoya)
[![Ko-fi](https://img.shields.io/badge/Tip-Ko%E2%80%91fi-FF5E5B?logo=kofi&logoColor=white)](https://ko-fi.com/lozoya)
![License](https://img.shields.io/badge/license-AGPL--3.0-blue)

**Global and local path planning**

Lozoya Path Planning provides a unified interface for classical, sampling-based, and optimization-based motion planning algorithms. It supports global and local planners such as A*, PRM, RRT*, CHOMP, TEB, DWA, and WASP (Waypoint Adaptive Spline Planner) for smooth and dynamically feasible trajectories.

The framework is designed to be modular, allowing users to combine planners, cost functions, and constraints across different domains—ground robots, aerial vehicles, or manipulators. Each planner follows a consistent API and integrates seamlessly with other Lozoya components like Lozoya Spline for curve generation and Lozoya Optimization for trajectory refinement.

**Key features:**

- Unified API for global and local planning.
- Built-in support for collision checking, spline smoothing, and time-parameterized trajectories.
- Extensible module system for adding new planners or cost functions.

Works in both 2D and 3D with real-time visualization hooks.

---

## Support This Work

Open source engineering takes a lot of time and coffee. If you would like to directly support ongoing research,
development, and maintenance of these tools, you can do so here:

[![Buy Me A Coffee](https://img.shields.io/badge/Donate-Buy%20Me%20A%20Coffee-FFDD00?logo=buymeacoffee&logoColor=white)](https://www.buymeacoffee.com/clozoya172b)

[![Patreon](https://img.shields.io/badge/Support-Patreon-051D34?logo=patreon&logoColor=white)](https://www.patreon.com/lozoya)

[![Ko-fi](https://img.shields.io/badge/Tip-Ko%E2%80%91fi-FF5E5B?logo=kofi&logoColor=white)](https://ko-fi.com/lozoya)

Your support helps keep the project healthy and moving forward.

---

## License

This project is licensed under the GNU Affero General Public License v3.0 (AGPL-3.0). Any modified version made
available to users over a network must also be released under the AGPL-3.0. See the LICENSE file for full details.

![License](https://img.shields.io/badge/license-AGPL--3.0-blue)

---
