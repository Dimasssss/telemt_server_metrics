# Server Metrics 2026-03-12 12:37:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 23931.4 (6h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 817663
telemt_connections_bad_total 1979
telemt_handshake_timeouts_total 6164
telemt_upstream_connect_attempt_total 4787
telemt_upstream_connect_success_total 4758
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 4787
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2575
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2177
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 329
telemt_me_reconnect_attempts_total 7420
telemt_me_reconnect_success_total 3526
telemt_me_reader_eof_total 3783
telemt_me_idle_close_by_peer_total 3783
telemt_me_route_drop_no_conn_total 290009
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 786290
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4125
telemt_desync_full_logged_total 1040
telemt_desync_suppressed_total 3085
telemt_desync_frames_bucket_total{bucket="1_2"} 1035
telemt_desync_frames_bucket_total{bucket="3_10"} 1494
telemt_desync_frames_bucket_total{bucket="gt_10"} 1596
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 3683
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 3513
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 157
telemt_user_connections_total{user="hello"} 786127
telemt_user_connections_current{user="hello"} 1677
telemt_user_octets_from_client{user="hello"} 13440036092 (12.52 GB)
telemt_user_octets_to_client{user="hello"} 222250944148 (206.99 GB)
telemt_user_unique_ips_current{user="hello"} 441
telemt_user_unique_ips_recent_window{user="hello"} 215
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 53551.6 (14h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 412625
telemt_connections_bad_total 5120
telemt_handshake_timeouts_total 21910
telemt_upstream_connect_attempt_total 13010
telemt_upstream_connect_success_total 13003
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 13010
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6407
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6580
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1055
telemt_me_reconnect_attempts_total 10200
telemt_me_reconnect_success_total 10143
telemt_me_reader_eof_total 10788
telemt_me_idle_close_by_peer_total 10788
telemt_me_route_drop_no_conn_total 118658
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 363578
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1193
telemt_desync_full_logged_total 386
telemt_desync_suppressed_total 807
telemt_desync_frames_bucket_total{bucket="1_2"} 476
telemt_desync_frames_bucket_total{bucket="3_10"} 404
telemt_desync_frames_bucket_total{bucket="gt_10"} 313
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 10237
telemt_me_writer_restored_same_endpoint_total 10134
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 364035
telemt_user_connections_current{user="hello"} 636
telemt_user_octets_from_client{user="hello"} 4876158467 (4.54 GB)
telemt_user_octets_to_client{user="hello"} 129437409150 (120.55 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 168
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 53551.6 (14h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 929715
telemt_connections_bad_total 5057
telemt_handshake_timeouts_total 69756
telemt_upstream_connect_attempt_total 13101
telemt_upstream_connect_success_total 13096
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 13101
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7149
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5890
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 862
telemt_me_reconnect_attempts_total 10149
telemt_me_reconnect_success_total 10062
telemt_me_reader_eof_total 10595
telemt_me_idle_close_by_peer_total 10595
telemt_me_route_drop_no_conn_total 229117
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 638360
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2914
telemt_desync_full_logged_total 875
telemt_desync_suppressed_total 2039
telemt_desync_frames_bucket_total{bucket="1_2"} 417
telemt_desync_frames_bucket_total{bucket="3_10"} 1032
telemt_desync_frames_bucket_total{bucket="gt_10"} 1465
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 10088
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 10021
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 638590
telemt_user_connections_current{user="hello"} 1024
telemt_user_octets_from_client{user="hello"} 8352863336 (7.78 GB)
telemt_user_octets_to_client{user="hello"} 201157142557 (187.34 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 294
telemt_user_unique_ips_recent_window{user="hello"} 168
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 53551.9 (14h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 520488
telemt_connections_bad_total 7637
telemt_handshake_timeouts_total 47862
telemt_upstream_connect_attempt_total 14420
telemt_upstream_connect_success_total 14362
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 14420
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8158
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6192
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 1267
telemt_me_reconnect_attempts_total 12912
telemt_me_reconnect_success_total 11681
telemt_me_reader_eof_total 12397
telemt_me_idle_close_by_peer_total 12397
telemt_me_route_drop_no_conn_total 171495
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 434543
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 877
telemt_desync_full_logged_total 306
telemt_desync_suppressed_total 571
telemt_desync_frames_bucket_total{bucket="1_2"} 255
telemt_desync_frames_bucket_total{bucket="3_10"} 364
telemt_desync_frames_bucket_total{bucket="gt_10"} 258
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 11803
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 11660
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 122
telemt_user_connections_total{user="hello"} 434366
telemt_user_connections_current{user="hello"} 627
telemt_user_octets_from_client{user="hello"} 4923674372 (4.59 GB)
telemt_user_octets_to_client{user="hello"} 169788942912 (158.13 GB)
telemt_user_unique_ips_current{user="hello"} 177
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 53551.8 (14h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 586101
telemt_connections_bad_total 1701
telemt_handshake_timeouts_total 4645
telemt_upstream_connect_attempt_total 17290
telemt_upstream_connect_success_total 17081
telemt_upstream_connect_fail_total 209
telemt_upstream_connect_attempts_per_request{bucket="1"} 17290
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8695
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8290
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 209
telemt_me_keepalive_timeout_total 967
telemt_me_reconnect_attempts_total 21617
telemt_me_reconnect_success_total 14393
telemt_me_reader_eof_total 15095
telemt_me_idle_close_by_peer_total 15095
telemt_me_seq_mismatch_total 22
telemt_me_route_drop_no_conn_total 196716
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 547722
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 26
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2289
telemt_desync_full_logged_total 772
telemt_desync_suppressed_total 1517
telemt_desync_frames_bucket_total{bucket="1_2"} 657
telemt_desync_frames_bucket_total{bucket="3_10"} 804
telemt_desync_frames_bucket_total{bucket="gt_10"} 828
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 14759
telemt_me_refill_failed_total 224
telemt_me_writer_restored_same_endpoint_total 14366
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 366
telemt_user_connections_total{user="hello"} 547636
telemt_user_connections_current{user="hello"} 697
telemt_user_octets_from_client{user="hello"} 6341277492 (5.91 GB)
telemt_user_octets_to_client{user="hello"} 139806838944 (130.21 GB)
telemt_user_unique_ips_current{user="hello"} 209
telemt_user_unique_ips_recent_window{user="hello"} 118
```