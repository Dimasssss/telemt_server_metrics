# Server Metrics 2026-03-12 11:05:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 18422.2 (5h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 618558
telemt_connections_bad_total 1489
telemt_handshake_timeouts_total 3621
telemt_upstream_connect_attempt_total 3531
telemt_upstream_connect_success_total 3509
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 3531
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1954
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1552
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 311
telemt_me_reconnect_attempts_total 6438
telemt_me_reconnect_success_total 2549
telemt_me_reader_eof_total 2761
telemt_me_idle_close_by_peer_total 2761
telemt_me_route_drop_no_conn_total 213968
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 595743
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2922
telemt_desync_full_logged_total 731
telemt_desync_suppressed_total 2191
telemt_desync_frames_bucket_total{bucket="1_2"} 731
telemt_desync_frames_bucket_total{bucket="3_10"} 1082
telemt_desync_frames_bucket_total{bucket="gt_10"} 1109
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 2696
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 2536
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 147
telemt_user_connections_total{user="hello"} 595607
telemt_user_connections_current{user="hello"} 1417
telemt_user_octets_from_client{user="hello"} 10596731720 (9.87 GB)
telemt_user_octets_to_client{user="hello"} 163595985984 (152.36 GB)
telemt_user_unique_ips_current{user="hello"} 386
telemt_user_unique_ips_recent_window{user="hello"} 227
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 48042.6 (13h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 330317
telemt_connections_bad_total 3511
telemt_handshake_timeouts_total 10770
telemt_upstream_connect_attempt_total 11973
telemt_upstream_connect_success_total 11967
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 11973
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5867
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6085
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 682
telemt_me_reconnect_attempts_total 9424
telemt_me_reconnect_success_total 9371
telemt_me_reader_eof_total 9962
telemt_me_idle_close_by_peer_total 9962
telemt_me_route_drop_no_conn_total 95343
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 296260
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 701
telemt_desync_full_logged_total 259
telemt_desync_suppressed_total 442
telemt_desync_frames_bucket_total{bucket="1_2"} 233
telemt_desync_frames_bucket_total{bucket="3_10"} 251
telemt_desync_frames_bucket_total{bucket="gt_10"} 217
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 9453
telemt_me_writer_restored_same_endpoint_total 9362
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 296691
telemt_user_connections_current{user="hello"} 709
telemt_user_octets_from_client{user="hello"} 4064418455 (3.79 GB)
telemt_user_octets_to_client{user="hello"} 106650494370 (99.33 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 172
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 48042.6 (13h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 801081
telemt_connections_bad_total 3987
telemt_handshake_timeouts_total 58889
telemt_upstream_connect_attempt_total 11958
telemt_upstream_connect_success_total 11953
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 11958
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6594
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5306
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 594
telemt_me_reconnect_attempts_total 9271
telemt_me_reconnect_success_total 9194
telemt_me_reader_eof_total 9669
telemt_me_idle_close_by_peer_total 9669
telemt_me_route_drop_no_conn_total 184579
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 523897
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2378
telemt_desync_full_logged_total 705
telemt_desync_suppressed_total 1673
telemt_desync_frames_bucket_total{bucket="1_2"} 304
telemt_desync_frames_bucket_total{bucket="3_10"} 820
telemt_desync_frames_bucket_total{bucket="gt_10"} 1254
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 9211
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 9153
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 524146
telemt_user_connections_current{user="hello"} 951
telemt_user_octets_from_client{user="hello"} 6858858756 (6.39 GB)
telemt_user_octets_to_client{user="hello"} 167997562817 (156.46 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 272
telemt_user_unique_ips_recent_window{user="hello"} 159
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 48042.9 (13h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 421810
telemt_connections_bad_total 2490
telemt_handshake_timeouts_total 35248
telemt_upstream_connect_attempt_total 12845
telemt_upstream_connect_success_total 12794
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 12845
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7264
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5521
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_timeout_total 858
telemt_me_reconnect_attempts_total 10424
telemt_me_reconnect_success_total 10384
telemt_me_reader_eof_total 11019
telemt_me_idle_close_by_peer_total 11019
telemt_me_route_drop_no_conn_total 140814
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 354696
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 721
telemt_desync_full_logged_total 253
telemt_desync_suppressed_total 468
telemt_desync_frames_bucket_total{bucket="1_2"} 221
telemt_desync_frames_bucket_total{bucket="3_10"} 302
telemt_desync_frames_bucket_total{bucket="gt_10"} 198
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 10455
telemt_me_writer_restored_same_endpoint_total 10363
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 354520
telemt_user_connections_current{user="hello"} 646
telemt_user_octets_from_client{user="hello"} 4161100624 (3.88 GB)
telemt_user_octets_to_client{user="hello"} 135228747112 (125.94 GB)
telemt_user_unique_ips_current{user="hello"} 183
telemt_user_unique_ips_recent_window{user="hello"} 119
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 48042.9 (13h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 479063
telemt_connections_bad_total 1369
telemt_handshake_timeouts_total 3620
telemt_upstream_connect_attempt_total 15486
telemt_upstream_connect_success_total 15300
telemt_upstream_connect_fail_total 186
telemt_upstream_connect_attempts_per_request{bucket="1"} 15486
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7923
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7292
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 79
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 186
telemt_me_keepalive_timeout_total 650
telemt_me_reconnect_attempts_total 14406
telemt_me_reconnect_success_total 12881
telemt_me_reader_eof_total 13393
telemt_me_idle_close_by_peer_total 13393
telemt_me_seq_mismatch_total 21
telemt_me_route_drop_no_conn_total 155798
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 449830
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1854
telemt_desync_full_logged_total 620
telemt_desync_suppressed_total 1234
telemt_desync_frames_bucket_total{bucket="1_2"} 555
telemt_desync_frames_bucket_total{bucket="3_10"} 632
telemt_desync_frames_bucket_total{bucket="gt_10"} 667
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 13052
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 12855
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 171
telemt_user_connections_total{user="hello"} 449754
telemt_user_connections_current{user="hello"} 887
telemt_user_octets_from_client{user="hello"} 5016858856 (4.67 GB)
telemt_user_octets_to_client{user="hello"} 110457595560 (102.87 GB)
telemt_user_unique_ips_current{user="hello"} 213
telemt_user_unique_ips_recent_window{user="hello"} 136
```