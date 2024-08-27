# Laravel-runner-command
command laravel queue runner and task schedule runner

## Task Schedule
```sh
sail artisan schedule:run >> /dev/null 2>&1
```

## Queue
```sh
sail artisan queue:work
```

## Queue specific
```sh
// running on database
sail artisan queue:work database

// running on redis
sail artisan queue:work redis
```

## Queue command Alternative
```js
sail artisan queue:listen
```
