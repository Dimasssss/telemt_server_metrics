# Server Metrics 2026-03-13 14:34:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 117361.6 (32h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3599664
telemt_connections_bad_total 37400
telemt_handshake_timeouts_total 64591
telemt_upstream_connect_attempt_total 22950
telemt_upstream_connect_success_total 22821
telemt_upstream_connect_fail_total 128
telemt_upstream_connect_attempts_per_request{bucket="1"} 22949
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11767
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10995
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 128
telemt_me_keepalive_timeout_total 2164
telemt_me_reconnect_attempts_total 27065
telemt_me_reconnect_success_total 16978
telemt_me_reader_eof_total 18253
telemt_me_idle_close_by_peer_total 18252
telemt_me_route_drop_no_conn_total 1335903
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3301994
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13546
telemt_desync_full_logged_total 3554
telemt_desync_suppressed_total 9992
telemt_desync_frames_bucket_total{bucket="1_2"} 3439
telemt_desync_frames_bucket_total{bucket="3_10"} 5129
telemt_desync_frames_bucket_total{bucket="gt_10"} 4978
telemt_pool_swap_total 97
telemt_me_writer_removed_unexpected_total 17529
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 16965
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 551
telemt_user_connections_total{user="hello"} 3301709
telemt_user_connections_current{user="hello"} 1692
telemt_user_octets_from_client{user="hello"} 45250374548 (42.14 GB)
telemt_user_octets_to_client{user="hello"} 1045767119220 (973.95 GB)
telemt_user_unique_ips_current{user="hello"} 478
telemt_user_unique_ips_recent_window{user="hello"} 278
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 17025.2 (4h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 239837
telemt_connections_bad_total 13654
telemt_handshake_timeouts_total 5882
telemt_upstream_connect_attempt_total 4157
telemt_upstream_connect_success_total 4078
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 4157
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2080
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1953
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_keepalive_timeout_total 78
telemt_me_reconnect_attempts_total 5483
telemt_me_reconnect_success_total 3194
telemt_me_reader_eof_total 3383
telemt_me_idle_close_by_peer_total 3383
telemt_me_route_drop_no_conn_total 87100
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 214028
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 847
telemt_desync_full_logged_total 206
telemt_desync_suppressed_total 641
telemt_desync_frames_bucket_total{bucket="1_2"} 150
telemt_desync_frames_bucket_total{bucket="3_10"} 416
telemt_desync_frames_bucket_total{bucket="gt_10"} 281
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 3299
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 3187
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 105
telemt_user_connections_total{user="hello"} 214053
telemt_user_connections_current{user="hello"} 514
telemt_user_octets_from_client{user="hello"} 2223067592 (2.07 GB)
telemt_user_octets_to_client{user="hello"} 61574445884 (57.35 GB)
telemt_user_unique_ips_current{user="hello"} 172
telemt_user_unique_ips_recent_window{user="hello"} 108
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 146982.1 (40h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2685176
telemt_connections_bad_total 27314
telemt_handshake_timeouts_total 178455
telemt_upstream_connect_attempt_total 33138
telemt_upstream_connect_success_total 33128
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 33138
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17219
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15783
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 121
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3240
telemt_me_reconnect_attempts_total 28012
telemt_me_reconnect_success_total 25465
telemt_me_reader_eof_total 27003
telemt_me_idle_close_by_peer_total 27002
telemt_me_route_drop_no_conn_total 903740
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2196120
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7869
telemt_desync_full_logged_total 2567
telemt_desync_suppressed_total 5302
telemt_desync_frames_bucket_total{bucket="1_2"} 1246
telemt_desync_frames_bucket_total{bucket="3_10"} 2870
telemt_desync_frames_bucket_total{bucket="gt_10"} 3753
telemt_pool_swap_total 138
telemt_me_writer_removed_unexpected_total 25762
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 25424
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 297
telemt_user_connections_total{user="hello"} 2195503
telemt_user_connections_current{user="hello"} 980
telemt_user_octets_from_client{user="hello"} 36545076292 (34.04 GB)
telemt_user_octets_to_client{user="hello"} 777875684877 (724.45 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 283
telemt_user_unique_ips_recent_window{user="hello"} 167
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 146982.5 (40h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1710922
telemt_connections_bad_total 18075
telemt_handshake_timeouts_total 124267
telemt_upstream_connect_attempt_total 46580
telemt_upstream_connect_success_total 44253
telemt_upstream_connect_fail_total 2190
telemt_upstream_connect_attempts_per_request{bucket="1"} 46306
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26645
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2189
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11846
telemt_me_reconnect_attempts_total 40042
telemt_me_reconnect_success_total 31073
telemt_me_reader_eof_total 33409
telemt_me_idle_close_by_peer_total 33402
telemt_me_route_drop_no_conn_total 611447
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1431230
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2877
telemt_desync_full_logged_total 928
telemt_desync_suppressed_total 1949
telemt_desync_frames_bucket_total{bucket="1_2"} 768
telemt_desync_frames_bucket_total{bucket="3_10"} 1199
telemt_desync_frames_bucket_total{bucket="gt_10"} 910
telemt_pool_swap_total 129
telemt_me_writer_removed_unexpected_total 31587
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 31049
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 514
telemt_user_connections_total{user="hello"} 1435945
telemt_user_connections_current{user="hello"} 744
telemt_user_octets_from_client{user="hello"} 22429664769 (20.89 GB)
telemt_user_octets_to_client{user="hello"} 552896377350 (514.92 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 208
telemt_user_unique_ips_recent_window{user="hello"} 119
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 16418.3 (4h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 259503
telemt_connections_bad_total 3907
telemt_handshake_timeouts_total 2520
telemt_upstream_connect_attempt_total 3464
telemt_upstream_connect_success_total 3352
telemt_upstream_connect_fail_total 112
telemt_upstream_connect_attempts_per_request{bucket="1"} 3464
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1603
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1745
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 112
telemt_me_keepalive_timeout_total 63
telemt_me_reconnect_attempts_total 10556
telemt_me_reconnect_success_total 2479
telemt_me_reader_eof_total 2759
telemt_me_idle_close_by_peer_total 2759
telemt_me_route_drop_no_conn_total 101995
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 242185
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 784
telemt_desync_full_logged_total 253
telemt_desync_suppressed_total 531
telemt_desync_frames_bucket_total{bucket="1_2"} 296
telemt_desync_frames_bucket_total{bucket="3_10"} 307
telemt_desync_frames_bucket_total{bucket="gt_10"} 181
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 2736
telemt_me_refill_failed_total 251
telemt_me_writer_restored_same_endpoint_total 2475
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 257
telemt_user_connections_total{user="hello"} 242167
telemt_user_connections_current{user="hello"} 819
telemt_user_octets_from_client{user="hello"} 2645516860 (2.46 GB)
telemt_user_octets_to_client{user="hello"} 79221521576 (73.78 GB)
telemt_user_unique_ips_current{user="hello"} 199
telemt_user_unique_ips_recent_window{user="hello"} 116
```