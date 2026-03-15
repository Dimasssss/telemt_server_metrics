# Server Metrics 2026-03-15 07:31:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 33424.1 (9h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 598475
telemt_connections_bad_total 19534
telemt_handshake_timeouts_total 4080
telemt_upstream_connect_attempt_total 7022
telemt_upstream_connect_success_total 6996
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 7022
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3681
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3306
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_reconnect_attempts_total 5331
telemt_me_reconnect_success_total 5303
telemt_me_reader_eof_total 5605
telemt_me_idle_close_by_peer_total 5605
telemt_me_route_drop_no_conn_total 186897
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 505885
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1380
telemt_desync_full_logged_total 435
telemt_desync_suppressed_total 945
telemt_desync_frames_bucket_total{bucket="1_2"} 285
telemt_desync_frames_bucket_total{bucket="3_10"} 497
telemt_desync_frames_bucket_total{bucket="gt_10"} 598
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 5372
telemt_me_writer_restored_same_endpoint_total 5292
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 505885
telemt_user_connections_current{user="hello"} 1668
telemt_user_octets_from_client{user="hello"} 6405693452 (5.97 GB)
telemt_user_octets_to_client{user="hello"} 182174134528 (169.66 GB)
telemt_user_unique_ips_current{user="hello"} 512
telemt_user_unique_ips_recent_window{user="hello"} 216
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 33425.0 (9h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 220560
telemt_connections_bad_total 18350
telemt_handshake_timeouts_total 8090
telemt_upstream_connect_attempt_total 9254
telemt_upstream_connect_success_total 9207
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 9254
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4994
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4146
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 18
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 7237
telemt_me_reconnect_success_total 7196
telemt_me_reader_eof_total 7614
telemt_me_idle_close_by_peer_total 7614
telemt_me_route_drop_no_conn_total 57546
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 183260
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 675
telemt_desync_full_logged_total 226
telemt_desync_suppressed_total 449
telemt_desync_frames_bucket_total{bucket="1_2"} 180
telemt_desync_frames_bucket_total{bucket="3_10"} 266
telemt_desync_frames_bucket_total{bucket="gt_10"} 229
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 7231
telemt_me_writer_restored_same_endpoint_total 7188
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 183541
telemt_user_connections_current{user="hello"} 486
telemt_user_octets_from_client{user="hello"} 2931627119 (2.73 GB)
telemt_user_octets_to_client{user="hello"} 67560899960 (62.92 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 184
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 33425.0 (9h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 406367
telemt_connections_bad_total 11651
telemt_handshake_timeouts_total 39085
telemt_upstream_connect_attempt_total 7566
telemt_upstream_connect_success_total 7533
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 7566
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3984
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3516
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_reconnect_attempts_total 5866
telemt_me_reconnect_success_total 5833
telemt_me_reader_eof_total 6174
telemt_me_idle_close_by_peer_total 6174
telemt_me_route_drop_no_conn_total 106113
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 330022
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 626
telemt_desync_full_logged_total 253
telemt_desync_suppressed_total 373
telemt_desync_frames_bucket_total{bucket="1_2"} 144
telemt_desync_frames_bucket_total{bucket="3_10"} 219
telemt_desync_frames_bucket_total{bucket="gt_10"} 263
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 5900
telemt_me_writer_restored_same_endpoint_total 5814
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 67
telemt_user_connections_total{user="hello"} 329820
telemt_user_connections_current{user="hello"} 981
telemt_user_octets_from_client{user="hello"} 5008484184 (4.66 GB)
telemt_user_octets_to_client{user="hello"} 135882106924 (126.55 GB)
telemt_user_unique_ips_current{user="hello"} 300
telemt_user_unique_ips_recent_window{user="hello"} 155
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 33424.8 (9h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 265643
telemt_connections_bad_total 45185
telemt_handshake_timeouts_total 17929
telemt_upstream_connect_attempt_total 10844
telemt_upstream_connect_success_total 10589
telemt_upstream_connect_fail_total 255
telemt_upstream_connect_attempts_per_request{bucket="1"} 10844
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5001
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5585
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 255
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 21533
telemt_me_reconnect_success_total 8897
telemt_me_reader_eof_total 9570
telemt_me_idle_close_by_peer_total 9570
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 65664
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 196524
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 28
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 341
telemt_desync_full_logged_total 90
telemt_desync_suppressed_total 251
telemt_desync_frames_bucket_total{bucket="1_2"} 87
telemt_desync_frames_bucket_total{bucket="3_10"} 148
telemt_desync_frames_bucket_total{bucket="gt_10"} 106
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 9365
telemt_me_refill_failed_total 394
telemt_me_writer_restored_same_endpoint_total 8871
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 468
telemt_user_connections_total{user="hello"} 196526
telemt_user_connections_current{user="hello"} 502
telemt_user_octets_from_client{user="hello"} 1710213820 (1.59 GB)
telemt_user_octets_to_client{user="hello"} 66208248172 (61.66 GB)
telemt_user_unique_ips_current{user="hello"} 187
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 33425.7 (9h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 203578
telemt_connections_bad_total 438
telemt_handshake_timeouts_total 1979
telemt_upstream_connect_attempt_total 7405
telemt_upstream_connect_success_total 7375
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 7405
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3289
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4081
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_reconnect_attempts_total 5711
telemt_me_reconnect_success_total 5684
telemt_me_reader_eof_total 6070
telemt_me_idle_close_by_peer_total 6070
telemt_me_route_drop_no_conn_total 62217
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 190814
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 822
telemt_desync_full_logged_total 256
telemt_desync_suppressed_total 566
telemt_desync_frames_bucket_total{bucket="1_2"} 240
telemt_desync_frames_bucket_total{bucket="3_10"} 347
telemt_desync_frames_bucket_total{bucket="gt_10"} 235
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 5741
telemt_me_writer_restored_same_endpoint_total 5676
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 190821
telemt_user_connections_current{user="hello"} 684
telemt_user_octets_from_client{user="hello"} 1952575652 (1.82 GB)
telemt_user_octets_to_client{user="hello"} 73784514472 (68.72 GB)
telemt_user_unique_ips_current{user="hello"} 200
telemt_user_unique_ips_recent_window{user="hello"} 102
```