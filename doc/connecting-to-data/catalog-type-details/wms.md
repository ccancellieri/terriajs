!!! note

  * `start` - the dataset's start time
  * `stop` - the dataset's stop time
  * `now` - the current system time. If the system time is after `Stop Time`, `Stop Time` is used. If the system time is before `Start Time`, `Start Time` is used.

This value is ignored if `Current Time` is specified

  * `nearest` - the nearest available discrete time to the current continuous time is used.
  * `next` - the discrete time equal to or after the current continuous time is used.
  * `previous` - the discrete time equal to or before the current continuous time is used.