# TASKS

## mission statement
- balloon is launched and a glider is autonomously released at some altitude that autonomously returns to the initial launch location while also broadcasting its telemetry

## system requirements
- continues to function at >80k-ft
- continuously broadcasts:
  + date
  + time
  + GPS location (lat, lon, alt)
  + heading
  + aircraft orientation
  + distance to home
  + temperature

## components
- weather balloon
  + size:
  + lift capacity:
- detach/release mechanism
  + consumables (fishing line, line cutter, etc.)
  + should mechanism stay with balloon or glider?
  + code to control this system
- navigation, control, and telemetry system
  + GPS
  + microSD data logger
  + IMU 9DOF
  + arduino or python MCU?
  + radio transmitter
  + thermistor
  + camera (not required)
  + code to control these systems
- glider
  + single servo
  + control rod
  + movable rudder
  + code to control these systems
- base-station
  + receiver
  + code to process and plot the data

## verification testing
- cold conditions
  + research and specify the flight conditions
  + stick it in the freezer with different amount of insulation
- low pressure
- RTL navigation
- aircraft control
- release mechanism and control
- sensor input
  + GPS
  + thermistor
- telemetry output
- telemetry receive at base-station
