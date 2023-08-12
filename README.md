  +-----------------+           +---------------+
  |    Gymnasium    |           |    Member     |
  +-----------------+           +---------------+
  | gymnasium_id    |<-------1  | member_id     |
  | name            |           | last_name     |
  | address         |           | first_name    |
  | telephone_number|           | address       |
  +-----------------+           | date_of_birth |
                                | gender        |
                                | gymnasium_id  |---------
                                +---------------+          |
                                                             |
                                +-------------+           |
                                |   Session   |           |
                                +-------------+           |
                                | session_id  |<----------+
                                | type_of_sport|
                                | schedule    |
                                | max_capacity|
                                | gymnasium_id|------------
                                +-------------+
                                        |
                                +-------|-------+
                                |   Coach       |
                                +---------------+
                                | coach_id      |
                                | last_name     |
                                | first_name    |
                                | age           |
                                | specialty     |
                                | session_id    |
                                +---------------+
