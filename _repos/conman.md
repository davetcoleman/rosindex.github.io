---
name: conman
description: Orocos-Based Controller Manager
tags: [control, orocos, realtime, controller]
default: jbohren
instances:
  #jbohren: {url: 'https://github.com/jbohren/conman', distro_branches: {hydro: master}}
  jbohren: {type: 'github', ns: 'jbohren', name: 'conman', distro_branches: {hydro: master}}
  RCPRG-ros-pkg: {type: 'github', ns: 'RCPRG-ros-pkg', name: 'conman', distro_branches: {hydro: master}}
---
