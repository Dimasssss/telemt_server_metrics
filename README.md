# Server Metrics 2026-03-11 02:32:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 43551.6 (12h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 850927
telemt_connections_bad_total 10044
telemt_handshake_timeouts_total 14559
telemt_upstream_connect_attempt_total 9501
telemt_upstream_connect_success_total 9492
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 9501
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4742
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4691
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 500
telemt_me_reconnect_attempts_total 18915
telemt_me_reconnect_success_total 7246
telemt_me_reader_eof_total 7918
telemt_me_idle_close_by_peer_total 7918
telemt_me_route_drop_no_conn_total 341897
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 800202
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3662
telemt_desync_full_logged_total 1033
telemt_desync_suppressed_total 2629
telemt_desync_frames_bucket_total{bucket="1_2"} 1072
telemt_desync_frames_bucket_total{bucket="3_10"} 1370
telemt_desync_frames_bucket_total{bucket="gt_10"} 1220
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 7673
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 7240
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 427
telemt_user_connections_total{user="hello"} 799936
telemt_user_connections_current{user="hello"} 545
telemt_user_octets_from_client{user="hello"} 10843422616 (10.10 GB)
telemt_user_octets_to_client{user="hello"} 239469409500 (223.02 GB)
telemt_user_unique_ips_current{user="hello"} 181
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 43608.4 (12h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 360575
telemt_connections_bad_total 2413
telemt_handshake_timeouts_total 18160
telemt_upstream_connect_attempt_total 17117
telemt_upstream_connect_success_total 14227
telemt_upstream_connect_fail_total 2890
telemt_upstream_connect_attempts_per_request{bucket="1"} 17117
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6249
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5737
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2032
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2890
telemt_me_keepalive_timeout_total 1741
telemt_me_reconnect_attempts_total 9883
telemt_me_reconnect_success_total 9066
telemt_me_reader_eof_total 9576
telemt_me_idle_close_by_peer_total 9574
telemt_me_route_drop_no_conn_total 177161
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 309047
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1788
telemt_desync_full_logged_total 514
telemt_desync_suppressed_total 1274
telemt_desync_frames_bucket_total{bucket="1_2"} 548
telemt_desync_frames_bucket_total{bucket="3_10"} 637
telemt_desync_frames_bucket_total{bucket="gt_10"} 603
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 9181
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 9045
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 115
telemt_user_connections_total{user="hello"} 311317
telemt_user_connections_current{user="hello"} 183
telemt_user_octets_from_client{user="hello"} 2925267430 (2.72 GB)
telemt_user_octets_to_client{user="hello"} 72959204844 (67.95 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 43608.2 (12h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 601395
telemt_connections_bad_total 4906
telemt_handshake_timeouts_total 34612
telemt_upstream_connect_attempt_total 11914
telemt_upstream_connect_success_total 11753
telemt_upstream_connect_fail_total 161
telemt_upstream_connect_attempts_per_request{bucket="1"} 11914
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6490
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5191
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 161
telemt_me_keepalive_timeout_total 536
telemt_me_reconnect_attempts_total 19531
telemt_me_reconnect_success_total 8465
telemt_me_reader_eof_total 9198
telemt_me_idle_close_by_peer_total 9198
telemt_me_route_drop_no_conn_total 204315
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 533095
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1546
telemt_desync_full_logged_total 451
telemt_desync_suppressed_total 1095
telemt_desync_frames_bucket_total{bucket="1_2"} 344
telemt_desync_frames_bucket_total{bucket="3_10"} 538
telemt_desync_frames_bucket_total{bucket="gt_10"} 664
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 8925
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 8454
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 460
telemt_user_connections_total{user="hello"} 533995
telemt_user_connections_current{user="hello"} 225
telemt_user_octets_from_client{user="hello"} 7007484749 (6.53 GB)
telemt_user_octets_to_client{user="hello"} 163758605853 (152.51 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 95
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 43608.7 (12h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 450768
telemt_connections_bad_total 41270
telemt_handshake_timeouts_total 43614
telemt_upstream_connect_attempt_total 12727
telemt_upstream_connect_success_total 12727
telemt_upstream_connect_attempts_per_request{bucket="1"} 12727
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7163
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5561
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 438
telemt_me_reconnect_attempts_total 11552
telemt_me_reconnect_success_total 10515
telemt_me_reader_eof_total 11151
telemt_me_idle_close_by_peer_total 11151
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 135236
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 352270
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 767
telemt_desync_full_logged_total 305
telemt_desync_suppressed_total 462
telemt_desync_frames_bucket_total{bucket="1_2"} 288
telemt_desync_frames_bucket_total{bucket="3_10"} 269
telemt_desync_frames_bucket_total{bucket="gt_10"} 210
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 10641
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 10496
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 126
telemt_user_connections_total{user="hello"} 351939
telemt_user_connections_current{user="hello"} 202
telemt_user_octets_from_client{user="hello"} 4331522080 (4.03 GB)
telemt_user_octets_to_client{user="hello"} 94312234876 (87.84 GB)
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 43608.4 (12h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 475170
telemt_connections_bad_total 5790
telemt_handshake_timeouts_total 3014
telemt_upstream_connect_attempt_total 12883
telemt_upstream_connect_success_total 12829
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 12883
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6630
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6082
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 115
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 527
telemt_me_reconnect_attempts_total 14353
telemt_me_reconnect_success_total 10578
telemt_me_reader_eof_total 11152
telemt_me_idle_close_by_peer_total 11152
telemt_me_route_drop_no_conn_total 154015
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 433563
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2311
telemt_desync_full_logged_total 900
telemt_desync_suppressed_total 1411
telemt_desync_frames_bucket_total{bucket="1_2"} 858
telemt_desync_frames_bucket_total{bucket="3_10"} 980
telemt_desync_frames_bucket_total{bucket="gt_10"} 473
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 10832
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 10578
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 254
telemt_user_connections_total{user="hello"} 433232
telemt_user_connections_current{user="hello"} 234
telemt_user_octets_from_client{user="hello"} 8496174124 (7.91 GB)
telemt_user_octets_to_client{user="hello"} 153299911952 (142.77 GB)
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 31
```