# Contents
This guide primarily concerns itself with maintaining consistency within UWRT's ROS2 systems

# Naming
## Topics
- Topic names can only include alphanumerics, plus `_` and `/`
- Topic names should be all-lowercase and use `snake_case`
- Related topic should be grouped together using `/`
    - The IMU publishes both an imu message and a pressure message:
        - `/mercury/vectornav/imu`
        - `/mercury/vectornav/pressure_bar`
- Units may be appended to topic names where appropriate
    - `/mercury/vectornav/pressure_bar`
    - Otherwise SI units may be assumed

## Custom Messages, Services, Actions
- File names should use `PascalCase` and use the appropriate file extension (`.msg`, `.srv`, `.action`)
- Member variables should use `snake_case` (i.e. `string cell_name`)
- Constants should use `UPPER_CASE`
