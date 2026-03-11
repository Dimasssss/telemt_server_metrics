# Server Metrics 2026-03-11 14:56:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 88172.0 (24h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2145821
telemt_connections_bad_total 34692
telemt_handshake_timeouts_total 52278
telemt_upstream_connect_attempt_total 18591
telemt_upstream_connect_success_total 18579
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 18591
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9360
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9127
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 4852
telemt_me_reconnect_attempts_total 30685
telemt_me_reconnect_success_total 14131
telemt_me_reader_eof_total 15302
telemt_me_idle_close_by_peer_total 15302
telemt_me_route_drop_no_conn_total 793341
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1963159
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10298
telemt_desync_full_logged_total 2788
telemt_desync_suppressed_total 7510
telemt_desync_frames_bucket_total{bucket="1_2"} 2560
telemt_desync_frames_bucket_total{bucket="3_10"} 3969
telemt_desync_frames_bucket_total{bucket="gt_10"} 3769
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 14801
telemt_me_refill_failed_total 514
telemt_me_writer_restored_same_endpoint_total 14125
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 670
telemt_user_connections_total{user="hello"} 1961642
telemt_user_connections_current{user="hello"} 1389
telemt_user_octets_from_client{user="hello"} 26424958116 (24.61 GB)
telemt_user_octets_to_client{user="hello"} 559379802592 (520.96 GB)
telemt_user_unique_ips_current{user="hello"} 377
telemt_user_unique_ips_recent_window{user="hello"} 217
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 88228.8 (24h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 800146
telemt_connections_bad_total 13242
telemt_handshake_timeouts_total 54510
telemt_upstream_connect_attempt_total 28018
telemt_upstream_connect_success_total 25067
telemt_upstream_connect_fail_total 2951
telemt_upstream_connect_attempts_per_request{bucket="1"} 28018
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11613
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11206
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2039
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2951
telemt_me_keepalive_timeout_total 2537
telemt_me_reconnect_attempts_total 19798
telemt_me_reconnect_success_total 17706
telemt_me_reader_eof_total 18755
telemt_me_idle_close_by_peer_total 18752
telemt_me_route_drop_no_conn_total 313715
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 678598
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2864
telemt_desync_full_logged_total 910
telemt_desync_suppressed_total 1954
telemt_desync_frames_bucket_total{bucket="1_2"} 888
telemt_desync_frames_bucket_total{bucket="3_10"} 1033
telemt_desync_frames_bucket_total{bucket="gt_10"} 943
telemt_pool_swap_total 72
telemt_me_writer_removed_unexpected_total 17967
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 17683
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 261
telemt_user_connections_total{user="hello"} 681074
telemt_user_connections_current{user="hello"} 543
telemt_user_octets_from_client{user="hello"} 7795304074 (7.26 GB)
telemt_user_octets_to_client{user="hello"} 192304811704 (179.10 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 157
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 88228.7 (24h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1388664
telemt_connections_bad_total 8457
telemt_handshake_timeouts_total 122890
telemt_upstream_connect_attempt_total 23391
telemt_upstream_connect_success_total 23112
telemt_upstream_connect_fail_total 279
telemt_upstream_connect_attempts_per_request{bucket="1"} 23391
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12455
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10536
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 121
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 279
telemt_me_keepalive_timeout_total 1570
telemt_me_reconnect_attempts_total 33718
telemt_me_reconnect_success_total 17605
telemt_me_reader_eof_total 18909
telemt_me_idle_close_by_peer_total 18909
telemt_me_route_drop_no_conn_total 503443
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1206034
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3181
telemt_desync_full_logged_total 943
telemt_desync_suppressed_total 2238
telemt_desync_frames_bucket_total{bucket="1_2"} 783
telemt_desync_frames_bucket_total{bucket="3_10"} 1201
telemt_desync_frames_bucket_total{bucket="gt_10"} 1197
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 18350
telemt_me_refill_failed_total 499
telemt_me_writer_restored_same_endpoint_total 17594
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 745
telemt_user_connections_total{user="hello"} 1205801
telemt_user_connections_current{user="hello"} 780
telemt_user_octets_from_client{user="hello"} 14501011073 (13.51 GB)
telemt_user_octets_to_client{user="hello"} 360628209685 (335.86 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 237
telemt_user_unique_ips_recent_window{user="hello"} 128
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 88229.1 (24h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 994963
telemt_connections_bad_total 77663
telemt_handshake_timeouts_total 95089
telemt_upstream_connect_attempt_total 23691
telemt_upstream_connect_success_total 23691
telemt_upstream_connect_attempts_per_request{bucket="1"} 23691
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12958
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10728
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 974
telemt_me_reconnect_attempts_total 20372
telemt_me_reconnect_success_total 19298
telemt_me_reader_eof_total 20468
telemt_me_idle_close_by_peer_total 20467
telemt_me_seq_mismatch_total 17
telemt_me_route_drop_no_conn_total 324801
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 795215
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 28
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1689
telemt_desync_full_logged_total 649
telemt_desync_suppressed_total 1040
telemt_desync_frames_bucket_total{bucket="1_2"} 601
telemt_desync_frames_bucket_total{bucket="3_10"} 600
telemt_desync_frames_bucket_total{bucket="gt_10"} 488
telemt_pool_swap_total 77
telemt_me_writer_removed_unexpected_total 19536
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 19270
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 238
telemt_user_connections_total{user="hello"} 794539
telemt_user_connections_current{user="hello"} 622
telemt_user_octets_from_client{user="hello"} 9262662872 (8.63 GB)
telemt_user_octets_to_client{user="hello"} 232670391396 (216.69 GB)
telemt_user_unique_ips_current{user="hello"} 162
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 88228.6 (24h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1096154
telemt_connections_bad_total 6936
telemt_handshake_timeouts_total 11139
telemt_upstream_connect_attempt_total 23874
telemt_upstream_connect_success_total 23768
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 23874
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12141
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11428
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 194
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_keepalive_timeout_total 1907
telemt_me_reconnect_attempts_total 23327
telemt_me_reconnect_success_total 19242
telemt_me_reader_eof_total 20293
telemt_me_idle_close_by_peer_total 20293
telemt_me_route_drop_no_conn_total 390213
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 996305
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3846
telemt_desync_full_logged_total 1408
telemt_desync_suppressed_total 2438
telemt_desync_frames_bucket_total{bucket="1_2"} 1339
telemt_desync_frames_bucket_total{bucket="3_10"} 1447
telemt_desync_frames_bucket_total{bucket="gt_10"} 1060
telemt_pool_swap_total 59
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 19619
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 19242
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 377
telemt_user_connections_total{user="hello"} 996024
telemt_user_connections_current{user="hello"} 764
telemt_user_octets_from_client{user="hello"} 14298541427 (13.32 GB)
telemt_user_octets_to_client{user="hello"} 350039635150 (326.00 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 207
telemt_user_unique_ips_recent_window{user="hello"} 97
```