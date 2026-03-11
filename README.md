# Server Metrics 2026-03-11 10:05:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 70710.4 (19h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1536553
telemt_connections_bad_total 23556
telemt_handshake_timeouts_total 40909
telemt_upstream_connect_attempt_total 14619
telemt_upstream_connect_success_total 14610
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 14619
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7411
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7133
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 788
telemt_me_reconnect_attempts_total 22731
telemt_me_reconnect_success_total 11043
telemt_me_reader_eof_total 11959
telemt_me_idle_close_by_peer_total 11959
telemt_me_route_drop_no_conn_total 566148
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1393994
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6906
telemt_desync_full_logged_total 1912
telemt_desync_suppressed_total 4994
telemt_desync_frames_bucket_total{bucket="1_2"} 1825
telemt_desync_frames_bucket_total{bucket="3_10"} 2608
telemt_desync_frames_bucket_total{bucket="gt_10"} 2473
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 11516
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 11037
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 473
telemt_user_connections_total{user="hello"} 1392576
telemt_user_connections_current{user="hello"} 1417
telemt_user_octets_from_client{user="hello"} 18233482540 (16.98 GB)
telemt_user_octets_to_client{user="hello"} 398666794572 (371.29 GB)
telemt_user_unique_ips_current{user="hello"} 371
telemt_user_unique_ips_recent_window{user="hello"} 218
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 70767.1 (19h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 588235
telemt_connections_bad_total 10180
telemt_handshake_timeouts_total 33853
telemt_upstream_connect_attempt_total 23664
telemt_upstream_connect_success_total 20735
telemt_upstream_connect_fail_total 2929
telemt_upstream_connect_attempts_per_request{bucket="1"} 23664
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9459
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9033
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2929
telemt_me_keepalive_timeout_total 2113
telemt_me_reconnect_attempts_total 15088
telemt_me_reconnect_success_total 14248
telemt_me_reader_eof_total 15092
telemt_me_idle_close_by_peer_total 15090
telemt_me_route_drop_no_conn_total 242730
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 498834
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2261
telemt_desync_full_logged_total 695
telemt_desync_suppressed_total 1566
telemt_desync_frames_bucket_total{bucket="1_2"} 754
telemt_desync_frames_bucket_total{bucket="3_10"} 811
telemt_desync_frames_bucket_total{bucket="gt_10"} 696
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 14417
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 14226
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 169
telemt_user_connections_total{user="hello"} 501070
telemt_user_connections_current{user="hello"} 545
telemt_user_octets_from_client{user="hello"} 4885765762 (4.55 GB)
telemt_user_octets_to_client{user="hello"} 139103993780 (129.55 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 70766.9 (19h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1021920
telemt_connections_bad_total 7606
telemt_handshake_timeouts_total 99527
telemt_upstream_connect_attempt_total 19144
telemt_upstream_connect_success_total 18907
telemt_upstream_connect_fail_total 236
telemt_upstream_connect_attempts_per_request{bucket="1"} 19143
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10312
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8503
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 92
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 236
telemt_me_keepalive_timeout_total 780
telemt_me_reconnect_attempts_total 26654
telemt_me_reconnect_success_total 14285
telemt_me_reader_eof_total 15326
telemt_me_idle_close_by_peer_total 15326
telemt_me_route_drop_no_conn_total 336497
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 875311
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2496
telemt_desync_full_logged_total 736
telemt_desync_suppressed_total 1760
telemt_desync_frames_bucket_total{bucket="1_2"} 600
telemt_desync_frames_bucket_total{bucket="3_10"} 914
telemt_desync_frames_bucket_total{bucket="gt_10"} 982
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 14858
telemt_me_refill_failed_total 383
telemt_me_writer_restored_same_endpoint_total 14274
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 573
telemt_user_connections_total{user="hello"} 876134
telemt_user_connections_current{user="hello"} 746
telemt_user_octets_from_client{user="hello"} 10355058953 (9.64 GB)
telemt_user_octets_to_client{user="hello"} 268388428797 (249.96 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 225
telemt_user_unique_ips_recent_window{user="hello"} 137
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 70767.3 (19h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 745247
telemt_connections_bad_total 66628
telemt_handshake_timeouts_total 71621
telemt_upstream_connect_attempt_total 19421
telemt_upstream_connect_success_total 19421
telemt_upstream_connect_attempts_per_request{bucket="1"} 19421
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10766
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8651
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 716
telemt_me_reconnect_attempts_total 16945
telemt_me_reconnect_success_total 15890
telemt_me_reader_eof_total 16861
telemt_me_idle_close_by_peer_total 16860
telemt_me_seq_mismatch_total 13
telemt_me_route_drop_no_conn_total 233523
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 584724
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1269
telemt_desync_full_logged_total 482
telemt_desync_suppressed_total 787
telemt_desync_frames_bucket_total{bucket="1_2"} 434
telemt_desync_frames_bucket_total{bucket="3_10"} 473
telemt_desync_frames_bucket_total{bucket="gt_10"} 362
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 16076
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 15866
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 186
telemt_user_connections_total{user="hello"} 584098
telemt_user_connections_current{user="hello"} 532
telemt_user_octets_from_client{user="hello"} 6745566508 (6.28 GB)
telemt_user_octets_to_client{user="hello"} 167713866020 (156.20 GB)
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 70767.0 (19h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 793191
telemt_connections_bad_total 6082
telemt_handshake_timeouts_total 7697
telemt_upstream_connect_attempt_total 19076
telemt_upstream_connect_success_total 18999
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 19076
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9798
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9043
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 156
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_keepalive_timeout_total 784
telemt_me_reconnect_attempts_total 19145
telemt_me_reconnect_success_total 15351
telemt_me_reader_eof_total 16233
telemt_me_idle_close_by_peer_total 16233
telemt_me_route_drop_no_conn_total 273555
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 719898
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3003
telemt_desync_full_logged_total 1136
telemt_desync_suppressed_total 1867
telemt_desync_frames_bucket_total{bucket="1_2"} 1052
telemt_desync_frames_bucket_total{bucket="3_10"} 1218
telemt_desync_frames_bucket_total{bucket="gt_10"} 733
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 15664
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 15351
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 313
telemt_user_connections_total{user="hello"} 719577
telemt_user_connections_current{user="hello"} 797
telemt_user_octets_from_client{user="hello"} 11175745679 (10.41 GB)
telemt_user_octets_to_client{user="hello"} 262881228762 (244.83 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 210
telemt_user_unique_ips_recent_window{user="hello"} 114
```