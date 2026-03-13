# Server Metrics 2026-03-13 03:15:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 76596.5 (21h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2126408
telemt_connections_bad_total 27999
telemt_handshake_timeouts_total 22830
telemt_upstream_connect_attempt_total 15185
telemt_upstream_connect_success_total 15101
telemt_upstream_connect_fail_total 84
telemt_upstream_connect_attempts_per_request{bucket="1"} 15185
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7782
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7275
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 84
telemt_me_keepalive_timeout_total 1290
telemt_me_reconnect_attempts_total 20121
telemt_me_reconnect_success_total 11259
telemt_me_reader_eof_total 12158
telemt_me_idle_close_by_peer_total 12157
telemt_me_route_drop_no_conn_total 816694
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1956824
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8754
telemt_desync_full_logged_total 2278
telemt_desync_suppressed_total 6476
telemt_desync_frames_bucket_total{bucket="1_2"} 2307
telemt_desync_frames_bucket_total{bucket="3_10"} 3157
telemt_desync_frames_bucket_total{bucket="gt_10"} 3290
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 11693
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 11246
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 434
telemt_user_connections_total{user="hello"} 1956268
telemt_user_connections_current{user="hello"} 671
telemt_user_octets_from_client{user="hello"} 28514688844 (26.56 GB)
telemt_user_octets_to_client{user="hello"} 677398035948 (630.88 GB)
telemt_user_unique_ips_current{user="hello"} 240
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 106216.9 (29h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 866241
telemt_connections_bad_total 11843
telemt_handshake_timeouts_total 35869
telemt_upstream_connect_attempt_total 27053
telemt_upstream_connect_success_total 27024
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 27053
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14006
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12928
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3459
telemt_me_reconnect_attempts_total 20217
telemt_me_reconnect_success_total 20107
telemt_me_reader_eof_total 21422
telemt_me_idle_close_by_peer_total 21422
telemt_me_route_drop_no_conn_total 278185
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 783035
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3102
telemt_desync_full_logged_total 975
telemt_desync_suppressed_total 2127
telemt_desync_frames_bucket_total{bucket="1_2"} 1257
telemt_desync_frames_bucket_total{bucket="3_10"} 1008
telemt_desync_frames_bucket_total{bucket="gt_10"} 837
telemt_pool_swap_total 108
telemt_me_writer_removed_unexpected_total 20302
telemt_me_writer_restored_same_endpoint_total 20098
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 195
telemt_user_connections_total{user="hello"} 784939
telemt_user_connections_current{user="hello"} 231
telemt_user_octets_from_client{user="hello"} 12528184992 (11.67 GB)
telemt_user_octets_to_client{user="hello"} 299989520695 (279.39 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 106216.8 (29h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1794958
telemt_connections_bad_total 10347
telemt_handshake_timeouts_total 119879
telemt_upstream_connect_attempt_total 24750
telemt_upstream_connect_success_total 24740
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 24750
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12999
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11643
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1619
telemt_me_reconnect_attempts_total 20381
telemt_me_reconnect_success_total 19116
telemt_me_reader_eof_total 20246
telemt_me_idle_close_by_peer_total 20245
telemt_me_route_drop_no_conn_total 583672
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1414616
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5042
telemt_desync_full_logged_total 1542
telemt_desync_suppressed_total 3500
telemt_desync_frames_bucket_total{bucket="1_2"} 807
telemt_desync_frames_bucket_total{bucket="3_10"} 1825
telemt_desync_frames_bucket_total{bucket="gt_10"} 2410
telemt_pool_swap_total 99
telemt_me_writer_removed_unexpected_total 19296
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 19075
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 180
telemt_user_connections_total{user="hello"} 1414210
telemt_user_connections_current{user="hello"} 394
telemt_user_octets_from_client{user="hello"} 22383800796 (20.85 GB)
telemt_user_octets_to_client{user="hello"} 507915209469 (473.03 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 106217.2 (29h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1118711
telemt_connections_bad_total 13144
telemt_handshake_timeouts_total 74047
telemt_upstream_connect_attempt_total 36980
telemt_upstream_connect_success_total 34703
telemt_upstream_connect_fail_total 2140
telemt_upstream_connect_attempts_per_request{bucket="1"} 36706
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21472
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13140
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2139
telemt_me_keepalive_timeout_total 11371
telemt_me_reconnect_attempts_total 32492
telemt_me_reconnect_success_total 23566
telemt_me_reader_eof_total 25440
telemt_me_idle_close_by_peer_total 25433
telemt_me_route_drop_no_conn_total 396737
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 959795
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1906
telemt_desync_full_logged_total 632
telemt_desync_suppressed_total 1274
telemt_desync_frames_bucket_total{bucket="1_2"} 529
telemt_desync_frames_bucket_total{bucket="3_10"} 746
telemt_desync_frames_bucket_total{bucket="gt_10"} 631
telemt_pool_swap_total 90
telemt_me_writer_removed_unexpected_total 23998
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 23542
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 432
telemt_user_connections_total{user="hello"} 964965
telemt_user_connections_current{user="hello"} 241
telemt_user_octets_from_client{user="hello"} 14655755281 (13.65 GB)
telemt_user_octets_to_client{user="hello"} 379720930938 (353.64 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 106216.9 (29h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1238226
telemt_connections_bad_total 12636
telemt_handshake_timeouts_total 9641
telemt_upstream_connect_attempt_total 33415
telemt_upstream_connect_success_total 33008
telemt_upstream_connect_fail_total 407
telemt_upstream_connect_attempts_per_request{bucket="1"} 33415
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16928
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15898
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 169
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 407
telemt_me_keepalive_timeout_total 1904
telemt_me_reconnect_attempts_total 41468
telemt_me_reconnect_success_total 27738
telemt_me_reader_eof_total 29188
telemt_me_idle_close_by_peer_total 29188
telemt_me_seq_mismatch_total 37
telemt_me_route_drop_no_conn_total 461969
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1145498
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 41
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4246
telemt_desync_full_logged_total 1512
telemt_desync_suppressed_total 2734
telemt_desync_frames_bucket_total{bucket="1_2"} 1281
telemt_desync_frames_bucket_total{bucket="3_10"} 1395
telemt_desync_frames_bucket_total{bucket="gt_10"} 1570
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 28485
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 27689
telemt_me_writer_restored_fallback_total 49
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 747
telemt_user_connections_total{user="hello"} 1145353
telemt_user_connections_current{user="hello"} 303
telemt_user_octets_from_client{user="hello"} 14151737872 (13.18 GB)
telemt_user_octets_to_client{user="hello"} 395823238528 (368.64 GB)
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 44
```