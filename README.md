# Server Metrics 2026-03-11 12:54:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 80816.3 (22h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1882782
telemt_connections_bad_total 27769
telemt_handshake_timeouts_total 48539
telemt_upstream_connect_attempt_total 16731
telemt_upstream_connect_success_total 16722
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 16731
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8447
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8204
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 876
telemt_me_reconnect_attempts_total 25475
telemt_me_reconnect_success_total 12647
telemt_me_reader_eof_total 13672
telemt_me_idle_close_by_peer_total 13672
telemt_me_route_drop_no_conn_total 692947
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1717582
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8950
telemt_desync_full_logged_total 2420
telemt_desync_suppressed_total 6530
telemt_desync_frames_bucket_total{bucket="1_2"} 2217
telemt_desync_frames_bucket_total{bucket="3_10"} 3441
telemt_desync_frames_bucket_total{bucket="gt_10"} 3292
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 13184
telemt_me_refill_failed_total 398
telemt_me_writer_restored_same_endpoint_total 12641
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 537
telemt_user_connections_total{user="hello"} 1716122
telemt_user_connections_current{user="hello"} 1466
telemt_user_octets_from_client{user="hello"} 22729854588 (21.17 GB)
telemt_user_octets_to_client{user="hello"} 487107149764 (453.65 GB)
telemt_user_unique_ips_current{user="hello"} 361
telemt_user_unique_ips_recent_window{user="hello"} 211
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 80873.0 (22h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 716940
telemt_connections_bad_total 13027
telemt_handshake_timeouts_total 50380
telemt_upstream_connect_attempt_total 26158
telemt_upstream_connect_success_total 23216
telemt_upstream_connect_fail_total 2942
telemt_upstream_connect_attempts_per_request{bucket="1"} 26158
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10688
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10280
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2039
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2942
telemt_me_keepalive_timeout_total 2432
telemt_me_reconnect_attempts_total 17087
telemt_me_reconnect_success_total 16225
telemt_me_reader_eof_total 17169
telemt_me_idle_close_by_peer_total 17166
telemt_me_route_drop_no_conn_total 281329
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 601793
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2683
telemt_desync_full_logged_total 847
telemt_desync_suppressed_total 1836
telemt_desync_frames_bucket_total{bucket="1_2"} 848
telemt_desync_frames_bucket_total{bucket="3_10"} 976
telemt_desync_frames_bucket_total{bucket="gt_10"} 859
telemt_pool_swap_total 67
telemt_me_writer_removed_unexpected_total 16433
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 16202
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 208
telemt_user_connections_total{user="hello"} 604098
telemt_user_connections_current{user="hello"} 543
telemt_user_octets_from_client{user="hello"} 6502672398 (6.06 GB)
telemt_user_octets_to_client{user="hello"} 173331575672 (161.43 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 80872.7 (22h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1231350
telemt_connections_bad_total 8109
telemt_handshake_timeouts_total 114952
telemt_upstream_connect_attempt_total 21668
telemt_upstream_connect_success_total 21405
telemt_upstream_connect_fail_total 262
telemt_upstream_connect_attempts_per_request{bucket="1"} 21667
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11606
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9695
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 262
telemt_me_keepalive_timeout_total 874
telemt_me_reconnect_attempts_total 31028
telemt_me_reconnect_success_total 16271
telemt_me_reader_eof_total 17473
telemt_me_idle_close_by_peer_total 17473
telemt_me_route_drop_no_conn_total 425370
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1062064
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2867
telemt_desync_full_logged_total 855
telemt_desync_suppressed_total 2012
telemt_desync_frames_bucket_total{bucket="1_2"} 694
telemt_desync_frames_bucket_total{bucket="3_10"} 1078
telemt_desync_frames_bucket_total{bucket="gt_10"} 1095
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 16947
telemt_me_refill_failed_total 457
telemt_me_writer_restored_same_endpoint_total 16260
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 676
telemt_user_connections_total{user="hello"} 1062450
telemt_user_connections_current{user="hello"} 813
telemt_user_octets_from_client{user="hello"} 12450359017 (11.60 GB)
telemt_user_octets_to_client{user="hello"} 319329672697 (297.40 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 232
telemt_user_unique_ips_recent_window{user="hello"} 146
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 80873.2 (22h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 889242
telemt_connections_bad_total 75969
telemt_handshake_timeouts_total 82785
telemt_upstream_connect_attempt_total 21999
telemt_upstream_connect_success_total 21999
telemt_upstream_connect_attempts_per_request{bucket="1"} 21999
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12035
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9960
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 872
telemt_me_reconnect_attempts_total 19037
telemt_me_reconnect_success_total 17971
telemt_me_reader_eof_total 19059
telemt_me_idle_close_by_peer_total 19058
telemt_me_seq_mismatch_total 16
telemt_me_route_drop_no_conn_total 285155
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 705830
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 27
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1483
telemt_desync_full_logged_total 578
telemt_desync_suppressed_total 905
telemt_desync_frames_bucket_total{bucket="1_2"} 533
telemt_desync_frames_bucket_total{bucket="3_10"} 536
telemt_desync_frames_bucket_total{bucket="gt_10"} 414
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 18191
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 17944
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 220
telemt_user_connections_total{user="hello"} 705188
telemt_user_connections_current{user="hello"} 515
telemt_user_octets_from_client{user="hello"} 8009246072 (7.46 GB)
telemt_user_octets_to_client{user="hello"} 202250517580 (188.36 GB)
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 80872.9 (22h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 963058
telemt_connections_bad_total 6807
telemt_handshake_timeouts_total 8967
telemt_upstream_connect_attempt_total 22047
telemt_upstream_connect_success_total 21952
telemt_upstream_connect_fail_total 95
telemt_upstream_connect_attempts_per_request{bucket="1"} 22047
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11267
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10501
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 180
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 95
telemt_me_keepalive_timeout_total 931
telemt_me_reconnect_attempts_total 21867
telemt_me_reconnect_success_total 17800
telemt_me_reader_eof_total 18784
telemt_me_idle_close_by_peer_total 18784
telemt_me_route_drop_no_conn_total 339506
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 874850
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3545
telemt_desync_full_logged_total 1305
telemt_desync_suppressed_total 2240
telemt_desync_frames_bucket_total{bucket="1_2"} 1226
telemt_desync_frames_bucket_total{bucket="3_10"} 1364
telemt_desync_frames_bucket_total{bucket="gt_10"} 955
telemt_pool_swap_total 55
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 18155
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 17800
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 355
telemt_user_connections_total{user="hello"} 874602
telemt_user_connections_current{user="hello"} 799
telemt_user_octets_from_client{user="hello"} 12882907539 (12.00 GB)
telemt_user_octets_to_client{user="hello"} 314601672850 (293.00 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 197
telemt_user_unique_ips_recent_window{user="hello"} 113
```