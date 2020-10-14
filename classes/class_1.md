# Class
EspressoMachine

# Attributes
1. group_heads (hash in the format {symbol:  boolean}, representing the name of the grouphead as the key and is_clean as a boolean)*
2. boiler_pressure (float)
3. last_service_date (datetime)
4. last_service_by (string)

# Methods
1. pull_shot (pulls an espress from one of the group_heads and also sets that group's clean status to false)
2. change_pressure (sets boiler_pressure)
3. service (services the machine and sets last_service_date, last_service_by)
4. backflush (backflushes one of the group_heads and also sets that group's clean status to true)


*I don't know how to represent this has very clearly.
