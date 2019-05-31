# springboot-scheduled
Springboot实现定时任务
SpringBoot实现定时任务有两种比较简单的方式
1、使用@Scheduled(cron = "")的方式，这种方式简单快捷，但是表达式写死无法改变
2、实现SchedulingConfigurer接口的configureTasks方法，可以改变cron表达式，实现动态定时任务
