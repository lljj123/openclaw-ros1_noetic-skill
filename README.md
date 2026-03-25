# ROS Skill Repository

This repository hosts **OpenClaw ROS skills**, starting with:

- `skills/ros1-noetic-general`

## Skill: `ros1-noetic-general`

A practical, reusable ROS1 Noetic skill for building, running, and debugging ROS systems.

### What it covers

- ROS1 environment checks and setup validation
- ROS graph inspection (nodes/topics/services)
- Interface and runtime diagnostics
- Common engineering patterns for ROS1 projects
- OpenClaw ↔ ROS1 adaptation guidance

### Included files

- `SKILL.md` — trigger conditions and operating workflow
- `references/*.md` — official docs, patterns, and implementation notes
- `scripts/` — helper scripts for environment and graph checks:
  - `ros1_env_check.sh`
  - `ros1_graph_probe.sh`
  - `ros1_interface_check.sh`
  - `move_forward_by_odom.py`

## Usage

Place this repository (or just the skill folder) where OpenClaw can load skills, then invoke ROS-related tasks in natural language.

Examples:

- "Check whether my ROS1 Noetic environment is healthy"
- "Inspect current ROS graph and key topics"
- "Help me debug why my node is not publishing"

## Notes

- Target stack: **ROS1 Noetic**
- Shell scripts are designed for **zsh** environments
- Keep robot motion tests low-risk and safety-first
