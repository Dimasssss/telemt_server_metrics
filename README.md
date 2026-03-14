# Server Metrics 2026-03-14 15:26:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 7755.8 (2h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 303258
telemt_connections_bad_total 8627
telemt_handshake_timeouts_total 3682
telemt_upstream_connect_attempt_total 1638
telemt_upstream_connect_success_total 1630
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1638
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 821
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 799
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 1972
telemt_me_reconnect_success_total 1188
telemt_me_reader_eof_total 1223
telemt_me_idle_close_by_peer_total 1223
telemt_me_route_drop_no_conn_total 120967
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 278511
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 648
telemt_desync_full_logged_total 213
telemt_desync_suppressed_total 435
telemt_desync_frames_bucket_total{bucket="1_2"} 155
telemt_desync_frames_bucket_total{bucket="3_10"} 242
telemt_desync_frames_bucket_total{bucket="gt_10"} 251
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1227
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 1179
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 278501
telemt_user_connections_current{user="hello"} 1656
telemt_user_octets_from_client{user="hello"} 4789859876 (4.46 GB)
telemt_user_octets_to_client{user="hello"} 84794922232 (78.97 GB)
telemt_user_unique_ips_current{user="hello"} 471
telemt_user_unique_ips_recent_window{user="hello"} 191
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 7761.2 (2h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 124404
telemt_connections_bad_total 10176
telemt_handshake_timeouts_total 4699
telemt_upstream_connect_attempt_total 1707
telemt_upstream_connect_success_total 1684
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 1707
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 964
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 657
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 212
telemt_me_reconnect_attempts_total 2012
telemt_me_reconnect_success_total 1240
telemt_me_reader_eof_total 1280
telemt_me_idle_close_by_peer_total 1280
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 38909
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 100358
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 488
telemt_desync_full_logged_total 126
telemt_desync_suppressed_total 362
telemt_desync_frames_bucket_total{bucket="1_2"} 205
telemt_desync_frames_bucket_total{bucket="3_10"} 159
telemt_desync_frames_bucket_total{bucket="gt_10"} 124
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1297
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 1229
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 100319
telemt_user_connections_current{user="hello"} 651
telemt_user_octets_from_client{user="hello"} 1362694052 (1.27 GB)
telemt_user_octets_to_client{user="hello"} 41750950020 (38.88 GB)
telemt_user_unique_ips_current{user="hello"} 200
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 7624.0 (2h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 245301
telemt_connections_bad_total 829
telemt_handshake_timeouts_total 54135
telemt_upstream_connect_attempt_total 1719
telemt_upstream_connect_success_total 1712
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 1719
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 899
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 810
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 5171
telemt_me_reconnect_success_total 1279
telemt_me_reader_eof_total 1386
telemt_me_idle_close_by_peer_total 1386
telemt_me_route_drop_no_conn_total 65508
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 176333
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 275
telemt_desync_full_logged_total 75
telemt_desync_suppressed_total 200
telemt_desync_frames_bucket_total{bucket="1_2"} 71
telemt_desync_frames_bucket_total{bucket="3_10"} 119
telemt_desync_frames_bucket_total{bucket="gt_10"} 85
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1396
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 1246
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 117
telemt_user_connections_total{user="hello"} 176259
telemt_user_connections_current{user="hello"} 1079
telemt_user_octets_from_client{user="hello"} 2545703908 (2.37 GB)
telemt_user_octets_to_client{user="hello"} 62545350512 (58.25 GB)
telemt_user_unique_ips_current{user="hello"} 289
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 7478.4 (2h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 124803
telemt_connections_bad_total 28347
telemt_handshake_timeouts_total 17156
telemt_upstream_connect_attempt_total 2019
telemt_upstream_connect_success_total 2018
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2019
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1050
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 904
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 37
telemt_me_reconnect_attempts_total 1601
telemt_me_reconnect_success_total 1591
telemt_me_reader_eof_total 1619
telemt_me_idle_close_by_peer_total 1619
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 28937
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 77786
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 152
telemt_desync_full_logged_total 54
telemt_desync_suppressed_total 98
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 53
telemt_desync_frames_bucket_total{bucket="gt_10"} 47
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1596
telemt_me_writer_restored_same_endpoint_total 1589
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 77750
telemt_user_connections_current{user="hello"} 452
telemt_user_octets_from_client{user="hello"} 1454930000 (1.36 GB)
telemt_user_octets_to_client{user="hello"} 23586979772 (21.97 GB)
telemt_user_unique_ips_current{user="hello"} 142
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 7773.8 (2h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 121645
telemt_connections_bad_total 320
telemt_handshake_timeouts_total 1844
telemt_upstream_connect_attempt_total 1868
telemt_upstream_connect_success_total 1825
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 1868
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 955
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 829
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 2052
telemt_me_reconnect_success_total 1390
telemt_me_reader_eof_total 1440
telemt_me_idle_close_by_peer_total 1440
telemt_me_route_drop_no_conn_total 41740
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 112278
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 353
telemt_desync_full_logged_total 140
telemt_desync_suppressed_total 213
telemt_desync_frames_bucket_total{bucket="1_2"} 132
telemt_desync_frames_bucket_total{bucket="3_10"} 112
telemt_desync_frames_bucket_total{bucket="gt_10"} 109
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1443
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 1372
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 112283
telemt_user_connections_current{user="hello"} 686
telemt_user_octets_from_client{user="hello"} 1701494472 (1.58 GB)
telemt_user_octets_to_client{user="hello"} 42370167876 (39.46 GB)
telemt_user_unique_ips_current{user="hello"} 204
telemt_user_unique_ips_recent_window{user="hello"} 97
```