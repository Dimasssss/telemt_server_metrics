# Server Metrics 2026-03-12 11:10:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 18727.8 (5h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 630352
telemt_connections_bad_total 1492
telemt_handshake_timeouts_total 3698
telemt_upstream_connect_attempt_total 3558
telemt_upstream_connect_success_total 3536
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 3558
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1969
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1564
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 312
telemt_me_reconnect_attempts_total 6465
telemt_me_reconnect_success_total 2575
telemt_me_reader_eof_total 2787
telemt_me_idle_close_by_peer_total 2787
telemt_me_route_drop_no_conn_total 218131
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 607108
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2993
telemt_desync_full_logged_total 748
telemt_desync_suppressed_total 2245
telemt_desync_frames_bucket_total{bucket="1_2"} 744
telemt_desync_frames_bucket_total{bucket="3_10"} 1107
telemt_desync_frames_bucket_total{bucket="gt_10"} 1142
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 2722
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 2562
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 147
telemt_user_connections_total{user="hello"} 606969
telemt_user_connections_current{user="hello"} 1685
telemt_user_octets_from_client{user="hello"} 10736594412 (10.00 GB)
telemt_user_octets_to_client{user="hello"} 166939256352 (155.47 GB)
telemt_user_unique_ips_current{user="hello"} 424
telemt_user_unique_ips_recent_window{user="hello"} 249
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 48348.3 (13h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 335445
telemt_connections_bad_total 3573
telemt_handshake_timeouts_total 11185
telemt_upstream_connect_attempt_total 12000
telemt_upstream_connect_success_total 11994
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 12000
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5881
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6098
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 683
telemt_me_reconnect_attempts_total 9451
telemt_me_reconnect_success_total 9398
telemt_me_reader_eof_total 9989
telemt_me_idle_close_by_peer_total 9989
telemt_me_route_drop_no_conn_total 96794
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 300608
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 729
telemt_desync_full_logged_total 263
telemt_desync_suppressed_total 466
telemt_desync_frames_bucket_total{bucket="1_2"} 245
telemt_desync_frames_bucket_total{bucket="3_10"} 258
telemt_desync_frames_bucket_total{bucket="gt_10"} 226
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 9480
telemt_me_writer_restored_same_endpoint_total 9389
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 301039
telemt_user_connections_current{user="hello"} 672
telemt_user_octets_from_client{user="hello"} 4097113615 (3.82 GB)
telemt_user_octets_to_client{user="hello"} 107644217638 (100.25 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 165
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 48348.1 (13h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 807731
telemt_connections_bad_total 4080
telemt_handshake_timeouts_total 59356
telemt_upstream_connect_attempt_total 11995
telemt_upstream_connect_success_total 11990
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 11995
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6611
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5326
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 594
telemt_me_reconnect_attempts_total 9308
telemt_me_reconnect_success_total 9230
telemt_me_reader_eof_total 9706
telemt_me_idle_close_by_peer_total 9706
telemt_me_route_drop_no_conn_total 187015
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 529849
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2403
telemt_desync_full_logged_total 713
telemt_desync_suppressed_total 1690
telemt_desync_frames_bucket_total{bucket="1_2"} 308
telemt_desync_frames_bucket_total{bucket="3_10"} 830
telemt_desync_frames_bucket_total{bucket="gt_10"} 1265
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 9248
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 9189
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 530097
telemt_user_connections_current{user="hello"} 962
telemt_user_octets_from_client{user="hello"} 7127542004 (6.64 GB)
telemt_user_octets_to_client{user="hello"} 169672235765 (158.02 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 266
telemt_user_unique_ips_recent_window{user="hello"} 152
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 48348.7 (13h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 427026
telemt_connections_bad_total 2491
telemt_handshake_timeouts_total 36637
telemt_upstream_connect_attempt_total 12888
telemt_upstream_connect_success_total 12837
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 12888
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7288
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5540
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_timeout_total 858
telemt_me_reconnect_attempts_total 10467
telemt_me_reconnect_success_total 10426
telemt_me_reader_eof_total 11062
telemt_me_idle_close_by_peer_total 11062
telemt_me_route_drop_no_conn_total 142569
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 358694
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 731
telemt_desync_full_logged_total 257
telemt_desync_suppressed_total 474
telemt_desync_frames_bucket_total{bucket="1_2"} 227
telemt_desync_frames_bucket_total{bucket="3_10"} 303
telemt_desync_frames_bucket_total{bucket="gt_10"} 201
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 10498
telemt_me_writer_restored_same_endpoint_total 10405
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 358519
telemt_user_connections_current{user="hello"} 605
telemt_user_octets_from_client{user="hello"} 4185457648 (3.90 GB)
telemt_user_octets_to_client{user="hello"} 136351356476 (126.99 GB)
telemt_user_unique_ips_current{user="hello"} 174
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 48348.5 (13h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 485192
telemt_connections_bad_total 1657
telemt_handshake_timeouts_total 3684
telemt_upstream_connect_attempt_total 15581
telemt_upstream_connect_success_total 15395
telemt_upstream_connect_fail_total 186
telemt_upstream_connect_attempts_per_request{bucket="1"} 15581
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7976
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7334
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 79
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 186
telemt_me_keepalive_timeout_total 651
telemt_me_reconnect_attempts_total 14501
telemt_me_reconnect_success_total 12976
telemt_me_reader_eof_total 13488
telemt_me_idle_close_by_peer_total 13488
telemt_me_seq_mismatch_total 21
telemt_me_route_drop_no_conn_total 158032
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 455224
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1884
telemt_desync_full_logged_total 627
telemt_desync_suppressed_total 1257
telemt_desync_frames_bucket_total{bucket="1_2"} 561
telemt_desync_frames_bucket_total{bucket="3_10"} 644
telemt_desync_frames_bucket_total{bucket="gt_10"} 679
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 13147
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 12950
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 171
telemt_user_connections_total{user="hello"} 455155
telemt_user_connections_current{user="hello"} 870
telemt_user_octets_from_client{user="hello"} 5059562580 (4.71 GB)
telemt_user_octets_to_client{user="hello"} 111912986220 (104.23 GB)
telemt_user_unique_ips_current{user="hello"} 209
telemt_user_unique_ips_recent_window{user="hello"} 135
```