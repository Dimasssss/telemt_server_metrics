# Server Metrics 2026-03-11 10:41:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 72853.9 (20h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1606485
telemt_connections_bad_total 24745
telemt_handshake_timeouts_total 41855
telemt_upstream_connect_attempt_total 15035
telemt_upstream_connect_success_total 15026
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 15035
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7608
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7351
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 801
telemt_me_reconnect_attempts_total 23058
telemt_me_reconnect_success_total 11366
telemt_me_reader_eof_total 12299
telemt_me_idle_close_by_peer_total 12299
telemt_me_route_drop_no_conn_total 592403
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1459244
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7373
telemt_desync_full_logged_total 2018
telemt_desync_suppressed_total 5355
telemt_desync_frames_bucket_total{bucket="1_2"} 1926
telemt_desync_frames_bucket_total{bucket="3_10"} 2792
telemt_desync_frames_bucket_total{bucket="gt_10"} 2655
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 11844
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 11360
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 478
telemt_user_connections_total{user="hello"} 1457823
telemt_user_connections_current{user="hello"} 1203
telemt_user_octets_from_client{user="hello"} 18915958180 (17.62 GB)
telemt_user_octets_to_client{user="hello"} 416867562892 (388.24 GB)
telemt_user_unique_ips_current{user="hello"} 335
telemt_user_unique_ips_recent_window{user="hello"} 170
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 72910.7 (20h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 615414
telemt_connections_bad_total 10183
telemt_handshake_timeouts_total 38581
telemt_upstream_connect_attempt_total 24116
telemt_upstream_connect_success_total 21184
telemt_upstream_connect_fail_total 2932
telemt_upstream_connect_attempts_per_request{bucket="1"} 24116
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9678
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9263
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2932
telemt_me_keepalive_timeout_total 2156
telemt_me_reconnect_attempts_total 15450
telemt_me_reconnect_success_total 14605
telemt_me_reader_eof_total 15471
telemt_me_idle_close_by_peer_total 15469
telemt_me_route_drop_no_conn_total 251610
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 520669
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2352
telemt_desync_full_logged_total 729
telemt_desync_suppressed_total 1623
telemt_desync_frames_bucket_total{bucket="1_2"} 777
telemt_desync_frames_bucket_total{bucket="3_10"} 844
telemt_desync_frames_bucket_total{bucket="gt_10"} 731
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 14785
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 14583
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 180
telemt_user_connections_total{user="hello"} 522895
telemt_user_connections_current{user="hello"} 487
telemt_user_octets_from_client{user="hello"} 5243416934 (4.88 GB)
telemt_user_octets_to_client{user="hello"} 146004453996 (135.98 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 138
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 72910.4 (20h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1064897
telemt_connections_bad_total 7707
telemt_handshake_timeouts_total 102979
telemt_upstream_connect_attempt_total 19647
telemt_upstream_connect_success_total 19403
telemt_upstream_connect_fail_total 244
telemt_upstream_connect_attempts_per_request{bucket="1"} 19647
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10577
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8733
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 244
telemt_me_keepalive_timeout_total 809
telemt_me_reconnect_attempts_total 28310
telemt_me_reconnect_success_total 14690
telemt_me_reader_eof_total 15785
telemt_me_idle_close_by_peer_total 15785
telemt_me_route_drop_no_conn_total 353033
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 913758
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2564
telemt_desync_full_logged_total 759
telemt_desync_suppressed_total 1805
telemt_desync_frames_bucket_total{bucket="1_2"} 610
telemt_desync_frames_bucket_total{bucket="3_10"} 954
telemt_desync_frames_bucket_total{bucket="gt_10"} 1000
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 15303
telemt_me_refill_failed_total 422
telemt_me_writer_restored_same_endpoint_total 14679
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 613
telemt_user_connections_total{user="hello"} 914590
telemt_user_connections_current{user="hello"} 695
telemt_user_octets_from_client{user="hello"} 10710581173 (9.98 GB)
telemt_user_octets_to_client{user="hello"} 278627684917 (259.49 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 213
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 72910.7 (20h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 775029
telemt_connections_bad_total 68574
telemt_handshake_timeouts_total 73673
telemt_upstream_connect_attempt_total 19879
telemt_upstream_connect_success_total 19879
telemt_upstream_connect_attempts_per_request{bucket="1"} 19879
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10971
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8904
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 771
telemt_me_reconnect_attempts_total 17316
telemt_me_reconnect_success_total 16258
telemt_me_reader_eof_total 17264
telemt_me_idle_close_by_peer_total 17263
telemt_me_seq_mismatch_total 13
telemt_me_route_drop_no_conn_total 244543
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 610047
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1355
telemt_desync_full_logged_total 518
telemt_desync_suppressed_total 837
telemt_desync_frames_bucket_total{bucket="1_2"} 473
telemt_desync_frames_bucket_total{bucket="3_10"} 499
telemt_desync_frames_bucket_total{bucket="gt_10"} 383
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 16451
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 16234
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 193
telemt_user_connections_total{user="hello"} 609418
telemt_user_connections_current{user="hello"} 463
telemt_user_octets_from_client{user="hello"} 7012113400 (6.53 GB)
telemt_user_octets_to_client{user="hello"} 174755944364 (162.75 GB)
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 72910.5 (20h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 828040
telemt_connections_bad_total 6086
telemt_handshake_timeouts_total 7804
telemt_upstream_connect_attempt_total 19545
telemt_upstream_connect_success_total 19463
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 19545
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10009
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9290
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 161
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_timeout_total 817
telemt_me_reconnect_attempts_total 19521
telemt_me_reconnect_success_total 15723
telemt_me_reader_eof_total 16617
telemt_me_idle_close_by_peer_total 16617
telemt_me_route_drop_no_conn_total 287529
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 751213
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3129
telemt_desync_full_logged_total 1168
telemt_desync_suppressed_total 1961
telemt_desync_frames_bucket_total{bucket="1_2"} 1076
telemt_desync_frames_bucket_total{bucket="3_10"} 1261
telemt_desync_frames_bucket_total{bucket="gt_10"} 792
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 16039
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 15723
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 316
telemt_user_connections_total{user="hello"} 750941
telemt_user_connections_current{user="hello"} 757
telemt_user_octets_from_client{user="hello"} 11444555331 (10.66 GB)
telemt_user_octets_to_client{user="hello"} 275045215782 (256.16 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 191
telemt_user_unique_ips_recent_window{user="hello"} 108
```