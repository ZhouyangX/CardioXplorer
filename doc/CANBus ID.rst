CANBus Message Table
======================

CANBus Message Information
--------------------------
.. list-table::
   :widths: 25 50
   :header-rows: 1

   * - CANBus ID
     - Information
   * - 0x10
     - Joystick Controller
   * - 0x20
     - Railing Responder
   * - 0x30
     - Rotation Responder

Message Breakdown
------------------
.. list-table:: CANBus0x10
   :widths: 25 50
   :header-rows: 1

   * - Byte Position
     - Messages
   * - 0 
     - Left Joystick - X movement
   * - 1
     - Left Joystick - Y movement
   * - 2
     - Right Joystick - X movement
   * - 3
     - Right Joystick - Y movement
   * - 4
     - Right Joystick - R3 Button
   * - 5
     - L1 Button
   * - 6
     - R1 Button
   * - 7
     - Unassigned

.. list-table:: CANBus0x20
   :widths: 25 50
   :header-rows: 1

   * - Byte Position
     - Messages
   * - 0 - 3
     - Stepper Motor (NEMA17) Position
   * - 4
     - Unassigned
   * - 5
     - Unassigned
   * - 6
     - Unassigned
   * - 7
     - Unassigned

.. list-table:: CANBus0x30
   :widths: 25 50
   :header-rows: 1

   * - Byte Position
     - Messages
   * - 0 - 3
     - Stepper Motor (NEMA 8 w/ Gearbox) Position
   * - 4
     - Servo Position
   * - 5
     - Unassigned
   * - 6
     - Unassigned
   * - 7
     - Unassigned
