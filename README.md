# Alldocube-M8-Refined_Kernel_GSI
Improved kernel for GSI

Version 1.7-stable coming soon. Strictly recommended to use with GSI.

Applied some tweaks from Meizu Pro 7 and 7 plus. Work in progress

Custom parameters:

system.num_limit_low_batt=
#/proc/hps/num_limit_low_batt
system.num_limit_power_serv=
#/proc/hps/num_limit_power_serv


system.num_limit_low_batt=*
#/proc/hps/num_limit_low_batt

system.num_limit_power_serv=*
#/proc/hps/num_limit_power_serv

system.num_limit_thermal=*
#/proc/hps/num_limit_thermal

system.num_limit_ultra_power_saving=*
#/proc/hps/num_limit_ultra_power_saving

system.vfs_cache_pressure=*
#/proc/sys/vm/vfs_cache_pressure

system.dirty_ratio=*
#/proc/sys/vm/dirty_ratio

system.dirty_background_ratio=*
#/proc/sys/vm/dirty_background_ratio

system.overcommit_ratio=*
#/proc/sys/vm/overcommit_ratio

system.swappiness=*
#/proc/sys/vm/swappiness
#/sys/fs/cgroup/memory/sw/memory.swappiness

system.encryption=unsupported
#/proc/sys/fs/ext4/features/encryption unsupported

system.scheduler=*
#/sys/block/zram0/queue/scheduler
#/sys/block/mmcblk1/queue/scheduler
#/sys/block/mmcblk0/queue/scheduler

system.add_random=*
#/sys/block/zram0/queue/add_random
#/sys/block/mmcblk1/queue/add_random
#/sys/block/mmcblk0/queue/add_random

system.read_ahead_kb=*
#/sys/block/zram0/queue/read_ahead_kb 
#/sys/block/mmcblk1/queue/read_ahead_kb 
#/sys/block/mmcblk0/queue/read_ahead_kb 

system.nr_requests=*
#/sys/block/zram0/queue/nr_requests
#/sys/block/mmcblk1/queue/nr_requests
#/sys/block/mmcblk0/queue/nr_requests

system.iostats=*
#/sys/block/zram0/queue/iostats
#/sys/block/mmcblk1/queue/iostats 
#/sys/block/mmcblk0/queue/iostats 

system.go_hispeed_load=*
#/sys/devices/system/cpu/cpufreq/interactive/go_hispeed_load 

system.min_sample_time=*
#/sys/devices/system/cpu/cpufreq/interactive/min_sample_time 

system.min_free_kbytes=*
#/proc/sys/vm/min_free_kbytes 

system.extra_free_kbytes=*
#/proc/sys/vm/extra_free_kbytes 

system.admin_reserve_kbytes=*
#/proc/sys/vm/admin_reserve_kbytes 

system.user_reserve_kbytes=*
#/proc/sys/vm/user_reserve_kbytes 

system.max_map_count=*
#/proc/sys/vm/max_map_count 

system.timer_migration=*
#/proc/sys/vm/timer_migration 

system.sched_migration_cost_ns=*
#/proc/sys/kernel/sched_migration_cost_ns 

system.threads-max=*
#/proc/sys/kernel/threads-max 

system.aio-max-nr=*
#/proc/sys/kernel/aio-max-nr 

system.mode=*
#/proc/ppm/mode 

system.dlpt_limit=*
#/proc/ppm/policy/dlpt_limit 

system.sysboost_freq=*
#/proc/ppm/policy/sysboost_freq 

system.hica_power_state=*
#/proc/ppm/policy/hica_power_state 

system.thermlmt=*
#/proc/thermlmt 

system.cpufreq_power_mode=*
#/proc/cpufreq/cpufreq_power_mode 

system.hica_is_limit_big_freq=*
#/proc/ppm/policy/hica_is_limit_big_freq 

system.gpufreq_limited_thermal_ignore=*
#/proc/gpufreq/gpufreq_limited_thermal_ignore 

system.gpufreq_volt_enable=*
#/proc/gpufreq/gpufreq_volt_enable 

system.lpt_enable=*
#/proc/gpufreq/lpt_enable 

system.event_notify=*
#/d/ged/hal/event_notify 

system.fps_upper_bound=*
#/d/ged/hal/fps_upper_bound 

system.custom_boost_gpu_freq=*
#/d/ged/hal/custom_boost_gpu_freq 

system.custom_upbound_gpu_freq=*
#/d/ged/hal/custom_upbound_gpu_freq 

system.perf_ioctl=0
#/proc/perfmgr/perf_ioctl freq 0
#/proc/perfmgr/perf_ioctl touch 0 
#/proc/perfmgr/perf_ioctl core 0

system.gpufreq_input_boost=*
#/proc/gpufreq/gpufreq_input_boost 

system.gpufreq_opp_max_freq=*
#/proc/gpufreq/gpufreq_opp_max_freq 

system.gpufreq_opp_max_freq=*
#/proc/gpufreq/gpufreq_opp_max_freq 

system.gpufreq_opp_max_freq=*
#/proc/gpufreq/gpufreq_opp_max_freq 

system.gpufreq_opp_freq=*
#/proc/gpufreq/gpufreq_opp_freq 

system.dvfs_enable=*
#/proc/mali/dvfs_enable 

system.gpufreq_limited_thermal_ignore=*
#/proc/gpufreq/gpufreq_limited_thermal_ignore 

system.gpufreq_limited_low_batt_volt_ignore=*
#/proc/gpufreq/gpufreq_limited_low_batt_volt_ignore 

system.gpufreq_limited_low_batt_volume_ignore=*
#/proc/gpufreq/gpufreq_limited_low_batt_volume_ignore 

system.gpufreq_limited_pbm_ignore=*
#/proc/gpufreq/gpufreq_limited_pbm_ignore 

system.gpufreq_limited_oc_ignore=*
#/proc/gpufreq/gpufreq_limited_oc_ignore 

system.gpufreq_state=*
#/proc/gpufreq/gpufreq_state 

system.gpu_power_policy=*
#/sys/devices/soc/13040000.mali/power_policy 

system.input_boost_cpu_num=*
#/proc/hps/input_boost_cpu_num 

system.rush_boost_enabled=*
#/proc/hps/rush_boost_enabled 

system.rush_boost_cpu_num=*
#/proc/hps/rush_boost_cpu_num 

system.input_boost_enabled=*
#/proc/hps/input_boost_enabled 

system.kernel_max=*
#/sys/devices/system/cpu/kernel_max 

system.clabcct=*
#/proc/driver/thermal/clabcct 

system.clbcct=*
#/proc/driver/thermal/clbcct

system.clabcct_lcmoff=*
#/proc/driver/thermal/clabcct_lcmoff 

system.clmutt=*
#/proc/driver/thermal/clmutt

system.clatm_setting=enabled
#/proc/driver/thermal/clatm_setting 0 3000 10 15 1 560 0 1000 0
#/proc/driver/thermal/clatm_setting 1 2000 15 30 1 460 8000 700 0

system.clfps_level=*
#/proc/driver/thermal/clfps_level 

system.clatm_gpu_threshold=*
#/proc/driver/thermal/clatm_gpu_threshold 

system.clfps=*
#/proc/driver/thermal/clfps 

system.clfps_adp=*
#/proc/driver/thermal/clfps_adp 

system.fps_tm=*
#/proc/driver/fps_tm 

system.thermal_limit=*
#/proc/ppm/policy/thermal_limit 

system.ksm_run=*
#/sys/kernel/mm/ksm/run 

system.ksm_sleep_millisecs=*
#/sys/kernel/mm/ksm/sleep_millisecs 

system.ksm_pages_to_scan=*
#/sys/kernel/mm/ksm/pages_to_scan ${system.ksm_pages_to_scan}
