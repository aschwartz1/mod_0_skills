# Class
Range

# Attributes
1. is_hot (boolean)
2. number_of_burners (integer)
3. number_of_burners_occupied (integer)
4. burner_heat_level (array of integers)

# Methods
1. check_temperature (uses burner_temps and sets is_hot if a temp above a threshold is found)
2. add_cookware (checks if number_of_burners_occupied < number_of_burners and if so increases number_of_burners_occupied)
3. remove_cookware (if number_of_burners_occupied > 0, decrements number_of_burners_occupied)
4. set_burner_level (sets the temperature of one of the indexes of burner_temps)
