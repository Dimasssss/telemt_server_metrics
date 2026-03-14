# Server Metrics 2026-03-14 15:21:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 7448.9 (2h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 292131
telemt_connections_bad_total 7711
telemt_handshake_timeouts_total 3603
telemt_upstream_connect_attempt_total 1561
telemt_upstream_connect_success_total 1553
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1561
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 788
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 755
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 1895
telemt_me_reconnect_success_total 1111
telemt_me_reader_eof_total 1144
telemt_me_idle_close_by_peer_total 1144
telemt_me_route_drop_no_conn_total 116180
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 268825
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 613
telemt_desync_full_logged_total 204
telemt_desync_suppressed_total 409
telemt_desync_frames_bucket_total{bucket="1_2"} 151
telemt_desync_frames_bucket_total{bucket="3_10"} 229
telemt_desync_frames_bucket_total{bucket="gt_10"} 233
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1148
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 1102
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 268816
telemt_user_connections_current{user="hello"} 1649
telemt_user_octets_from_client{user="hello"} 4572433544 (4.26 GB)
telemt_user_octets_to_client{user="hello"} 81630977424 (76.02 GB)
telemt_user_unique_ips_current{user="hello"} 449
telemt_user_unique_ips_recent_window{user="hello"} 203
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 7454.3 (2h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 119424
telemt_connections_bad_total 9681
telemt_handshake_timeouts_total 4594
telemt_upstream_connect_attempt_total 1667
telemt_upstream_connect_success_total 1644
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 1667
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 944
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 640
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 177
telemt_me_reconnect_attempts_total 1972
telemt_me_reconnect_success_total 1200
telemt_me_reader_eof_total 1241
telemt_me_idle_close_by_peer_total 1241
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 37463
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 96340
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 481
telemt_desync_full_logged_total 122
telemt_desync_suppressed_total 359
telemt_desync_frames_bucket_total{bucket="1_2"} 199
telemt_desync_frames_bucket_total{bucket="3_10"} 158
telemt_desync_frames_bucket_total{bucket="gt_10"} 124
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1257
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 1189
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 96305
telemt_user_connections_current{user="hello"} 733
telemt_user_octets_from_client{user="hello"} 1326351908 (1.24 GB)
telemt_user_octets_to_client{user="hello"} 40371899112 (37.60 GB)
telemt_user_unique_ips_current{user="hello"} 221
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 7317.3 (2h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 236334
telemt_connections_bad_total 828
telemt_handshake_timeouts_total 53531
telemt_upstream_connect_attempt_total 1666
telemt_upstream_connect_success_total 1661
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 1666
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 875
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 783
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 3844
telemt_me_reconnect_success_total 1232
telemt_me_reader_eof_total 1299
telemt_me_idle_close_by_peer_total 1299
telemt_me_route_drop_no_conn_total 63334
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 169464
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 260
telemt_desync_full_logged_total 72
telemt_desync_suppressed_total 188
telemt_desync_frames_bucket_total{bucket="1_2"} 69
telemt_desync_frames_bucket_total{bucket="3_10"} 111
telemt_desync_frames_bucket_total{bucket="gt_10"} 80
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1309
telemt_me_refill_failed_total 81
telemt_me_writer_restored_same_endpoint_total 1199
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 169386
telemt_user_connections_current{user="hello"} 933
telemt_user_octets_from_client{user="hello"} 2494722080 (2.32 GB)
telemt_user_octets_to_client{user="hello"} 59803522968 (55.70 GB)
telemt_user_unique_ips_current{user="hello"} 271
telemt_user_unique_ips_recent_window{user="hello"} 155
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 7171.7 (1h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 119289
telemt_connections_bad_total 26781
telemt_handshake_timeouts_total 16681
telemt_upstream_connect_attempt_total 1902
telemt_upstream_connect_success_total 1901
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1902
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 998
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 847
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 1527
telemt_me_reconnect_success_total 1518
telemt_me_reader_eof_total 1527
telemt_me_idle_close_by_peer_total 1527
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 27738
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 74335
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 149
telemt_desync_full_logged_total 53
telemt_desync_suppressed_total 96
telemt_desync_frames_bucket_total{bucket="1_2"} 50
telemt_desync_frames_bucket_total{bucket="3_10"} 53
telemt_desync_frames_bucket_total{bucket="gt_10"} 46
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1523
telemt_me_writer_restored_same_endpoint_total 1516
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 74300
telemt_user_connections_current{user="hello"} 430
telemt_user_octets_from_client{user="hello"} 1407783364 (1.31 GB)
telemt_user_octets_to_client{user="hello"} 22400542288 (20.86 GB)
telemt_user_unique_ips_current{user="hello"} 134
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 7467.2 (2h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 117570
telemt_connections_bad_total 319
telemt_handshake_timeouts_total 1817
telemt_upstream_connect_attempt_total 1785
telemt_upstream_connect_success_total 1742
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 1785
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 905
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 797
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 1969
telemt_me_reconnect_success_total 1307
telemt_me_reader_eof_total 1356
telemt_me_idle_close_by_peer_total 1356
telemt_me_route_drop_no_conn_total 40445
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 108429
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 350
telemt_desync_full_logged_total 138
telemt_desync_suppressed_total 212
telemt_desync_frames_bucket_total{bucket="1_2"} 131
telemt_desync_frames_bucket_total{bucket="3_10"} 112
telemt_desync_frames_bucket_total{bucket="gt_10"} 107
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1359
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 1289
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 108433
telemt_user_connections_current{user="hello"} 758
telemt_user_octets_from_client{user="hello"} 1658888080 (1.54 GB)
telemt_user_octets_to_client{user="hello"} 40464492756 (37.69 GB)
telemt_user_unique_ips_current{user="hello"} 210
telemt_user_unique_ips_recent_window{user="hello"} 91
```