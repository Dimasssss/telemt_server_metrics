# Server Metrics 2026-03-11 08:59:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 66732.9 (18h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1397738
telemt_connections_bad_total 15748
telemt_handshake_timeouts_total 40311
telemt_upstream_connect_attempt_total 13953
telemt_upstream_connect_success_total 13944
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 13953
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7058
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6823
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 758
telemt_me_reconnect_attempts_total 22239
telemt_me_reconnect_success_total 10553
telemt_me_reader_eof_total 11430
telemt_me_idle_close_by_peer_total 11430
telemt_me_route_drop_no_conn_total 513461
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1267588
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6225
telemt_desync_full_logged_total 1721
telemt_desync_suppressed_total 4504
telemt_desync_frames_bucket_total{bucket="1_2"} 1637
telemt_desync_frames_bucket_total{bucket="3_10"} 2366
telemt_desync_frames_bucket_total{bucket="gt_10"} 2222
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 11019
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 10547
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 466
telemt_user_connections_total{user="hello"} 1267255
telemt_user_connections_current{user="hello"} 1408
telemt_user_octets_from_client{user="hello"} 16812268676 (15.66 GB)
telemt_user_octets_to_client{user="hello"} 365338306312 (340.25 GB)
telemt_user_unique_ips_current{user="hello"} 369
telemt_user_unique_ips_recent_window{user="hello"} 220
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 66789.6 (18h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 539495
telemt_connections_bad_total 9118
telemt_handshake_timeouts_total 29770
telemt_upstream_connect_attempt_total 22868
telemt_upstream_connect_success_total 19942
telemt_upstream_connect_fail_total 2926
telemt_upstream_connect_attempts_per_request{bucket="1"} 22868
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9068
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8631
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2926
telemt_me_keepalive_timeout_total 2077
telemt_me_reconnect_attempts_total 14469
telemt_me_reconnect_success_total 13634
telemt_me_reader_eof_total 14434
telemt_me_idle_close_by_peer_total 14432
telemt_me_route_drop_no_conn_total 226906
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 457271
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2144
telemt_desync_full_logged_total 659
telemt_desync_suppressed_total 1485
telemt_desync_frames_bucket_total{bucket="1_2"} 715
telemt_desync_frames_bucket_total{bucket="3_10"} 771
telemt_desync_frames_bucket_total{bucket="gt_10"} 658
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 13794
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 13612
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 160
telemt_user_connections_total{user="hello"} 459512
telemt_user_connections_current{user="hello"} 503
telemt_user_octets_from_client{user="hello"} 4461488906 (4.16 GB)
telemt_user_octets_to_client{user="hello"} 122866350704 (114.43 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 66789.5 (18h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 931247
telemt_connections_bad_total 7259
telemt_handshake_timeouts_total 80561
telemt_upstream_connect_attempt_total 18009
telemt_upstream_connect_success_total 17789
telemt_upstream_connect_fail_total 220
telemt_upstream_connect_attempts_per_request{bucket="1"} 18009
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9695
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8005
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 220
telemt_me_keepalive_timeout_total 757
telemt_me_reconnect_attempts_total 25715
telemt_me_reconnect_success_total 13354
telemt_me_reader_eof_total 14364
telemt_me_idle_close_by_peer_total 14364
telemt_me_route_drop_no_conn_total 306426
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 805390
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2317
telemt_desync_full_logged_total 686
telemt_desync_suppressed_total 1631
telemt_desync_frames_bucket_total{bucket="1_2"} 561
telemt_desync_frames_bucket_total{bucket="3_10"} 840
telemt_desync_frames_bucket_total{bucket="gt_10"} 916
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 13909
telemt_me_refill_failed_total 383
telemt_me_writer_restored_same_endpoint_total 13343
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 555
telemt_user_connections_total{user="hello"} 806190
telemt_user_connections_current{user="hello"} 728
telemt_user_octets_from_client{user="hello"} 9565041881 (8.91 GB)
telemt_user_octets_to_client{user="hello"} 243192312149 (226.49 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 221
telemt_user_unique_ips_recent_window{user="hello"} 115
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 66790.0 (18h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 688047
telemt_connections_bad_total 62554
telemt_handshake_timeouts_total 67399
telemt_upstream_connect_attempt_total 18481
telemt_upstream_connect_success_total 18481
telemt_upstream_connect_attempts_per_request{bucket="1"} 18481
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10295
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8182
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 691
telemt_me_reconnect_attempts_total 16180
telemt_me_reconnect_success_total 15127
telemt_me_reader_eof_total 16063
telemt_me_idle_close_by_peer_total 16062
telemt_me_seq_mismatch_total 12
telemt_me_route_drop_no_conn_total 214043
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 536662
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1242
telemt_desync_full_logged_total 468
telemt_desync_suppressed_total 774
telemt_desync_frames_bucket_total{bucket="1_2"} 415
telemt_desync_frames_bucket_total{bucket="3_10"} 470
telemt_desync_frames_bucket_total{bucket="gt_10"} 357
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 15304
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 15104
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 177
telemt_user_connections_total{user="hello"} 536036
telemt_user_connections_current{user="hello"} 533
telemt_user_octets_from_client{user="hello"} 6311931900 (5.88 GB)
telemt_user_octets_to_client{user="hello"} 151801531908 (141.38 GB)
telemt_user_unique_ips_current{user="hello"} 157
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 66789.8 (18h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 728393
telemt_connections_bad_total 5982
telemt_handshake_timeouts_total 6869
telemt_upstream_connect_attempt_total 18281
telemt_upstream_connect_success_total 18207
telemt_upstream_connect_fail_total 74
telemt_upstream_connect_attempts_per_request{bucket="1"} 18281
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9389
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8669
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 147
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 74
telemt_me_keepalive_timeout_total 747
telemt_me_reconnect_attempts_total 18526
telemt_me_reconnect_success_total 14734
telemt_me_reader_eof_total 15580
telemt_me_idle_close_by_peer_total 15580
telemt_me_route_drop_no_conn_total 246043
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 660041
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2862
telemt_desync_full_logged_total 1082
telemt_desync_suppressed_total 1780
telemt_desync_frames_bucket_total{bucket="1_2"} 1002
telemt_desync_frames_bucket_total{bucket="3_10"} 1188
telemt_desync_frames_bucket_total{bucket="gt_10"} 672
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 15040
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 14734
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 306
telemt_user_connections_total{user="hello"} 659729
telemt_user_connections_current{user="hello"} 708
telemt_user_octets_from_client{user="hello"} 10640293939 (9.91 GB)
telemt_user_octets_to_client{user="hello"} 237262305258 (220.97 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 186
telemt_user_unique_ips_recent_window{user="hello"} 113
```