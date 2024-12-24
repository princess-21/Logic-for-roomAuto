# Logic-for-roomAuto

Here's a shorter, simplified version of the README:

---

# Hostel Room Assignment System

A **Hostel Room Assignment System** for assigning students to rooms in different hostels. The system uses the **Fisher-Yates shuffle** algorithm to randomly assign students to available blocks and rooms.

## Features

- **Hostel Management**: Create and manage multiple hostels and blocks.
- **Room Assignment**: Randomly assign students to available rooms in a block.
- **Randomized Name Assignment**: Shuffle student names before assignment.

## Business Logic

This system is a **business logic prototype**. It handles the core functionality of assigning students to rooms in hostels. Future updates will improve the logic, add a user interface, and integrate additional features.

## How It Works

1. **Admin Class**: Manages creation of hostels, blocks, and rooms.
2. **Hostel Class**: Manages blocks and room availability.
3. **Person Class**: Assigns students to rooms randomly.
4. **Fisher-Yates Shuffle**: Randomizes student names to ensure fairness.

## Usage

1. **Create Hostels**: `Admin.createHostel(hostelName)`
2. **Add Blocks**: `Admin.addBlockToHostel(hostel, blockId, blockName, roomMin, roomMax)`
3. **Assign Students**: Randomly assign students by creating `Person` instances.

## Future Updates

- Prototype Demo of room autonmation system
- User Interface for hostel management
- Deploying to netlify


## License

MIT License - see the [LICENSE](LICENSE) file for details.

---

This version is concise and highlights the main points of the system.
