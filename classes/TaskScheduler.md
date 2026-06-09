# TaskScheduler

**Superclass:** [Instance](Instance.md)

TaskScheduler is a read-only settings class for the Roblox Studio's _Task Scheduler_ feature. It manages the average duty cycle and task scheduler rate.

## Tags
- NotCreatable
- Service
- NotReplicated

## Properties
### `TaskScheduler.SchedulerDutyCycle`
- **Type:** `double`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** The average time divided by the average interval of the duty cycle.

### `TaskScheduler.SchedulerRate`
- **Type:** `double`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** The current average rate of the task scheduler.

### `TaskScheduler.ThreadPoolConfig`
- **Type:** `ThreadPoolConfig`
- **Summary:** The specified thread pooling configuration for the task scheduler.

### `TaskScheduler.ThreadPoolSize`
- **Type:** `int`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** The current size of the thread pool.
