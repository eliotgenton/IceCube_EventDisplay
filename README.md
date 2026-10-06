# IceCube Event Display

**Open it: <https://eliotgenton.github.io/IceCube_EventDisplay/>**

An interactive 3D display of muon-neutrino events in the IceCube detector at the South Pole, in the browser, with nothing to install. The events are simulated with [Prometheus](https://github.com/Harvard-Neutrino/prometheus), the open-source neutrino-telescope simulation, on its IceCube geometry (5160 optical modules on 86 strings, 1.45 to 2.45 km deep in the ice).

* Space plays an event, 1 to 5 change the camera, B switches day and night, H lists every key.
* Colour the hits by "true photon origin" to see which light came from the muon and which from the hadronic shower.
* Every event passed Prometheus's multiplicity trigger (more than 8 modules with more than 5 photons each).

These are simulated photons, not IceCube data: there is no detector electronics, noise or reconstruction. This page is not an IceCube Collaboration product.

The display and the Prometheus exporter: <https://github.com/eliotgenton/km3net_event_display/tree/prometheus> (`docs/prometheus.md`). Made by Eliot Genton (Harvard). MIT licence.
