# Object
Zeteo Coffee's Nuova Simonelli Aurelia II

# Attributes
1. group_heads = {
  left: true,
  right: true
}
2. boiler_pressure = 1.2
3. last_service_date = 2020-09-30
4. last_service_by = "Charles Boyle"

# Methods
1. pull_shot => group_heads = {
  left: false,   # left was used for espresso, so now it's dirty
  right: true    # right wasn't used, so it stays the same
}
2. change_pressure => 1.3
3. service => last_service_date = 2020-10-13, last_service_by = "Alex Schwartz"
4. backflush => group_heads = {
  left: true,    # cleaned the left group_head
  right: true    # still didn't touch the right group_head
}
