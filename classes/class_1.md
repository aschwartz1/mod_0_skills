# Class
EspressoMachine

# Attributes
1. group_heads (hash)
2. boiler_pressure (float)
3. last_service_date (datetime)
4. last_service_by (string)

# Methods
1. pull_shot (uses a group head from group_heads and pulls an espresso shot)
2. change_pressure (sets boiler_pressure)
3. service (services the machine and sets last_service_date, last_service_by)
4. backflush (uses a group head from group_heads backflushes it)
