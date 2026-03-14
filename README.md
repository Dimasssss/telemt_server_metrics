# Server Metrics 2026-03-14 23:48:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 5627.0 (1h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 79294
telemt_connections_bad_total 951
telemt_handshake_timeouts_total 338
telemt_upstream_connect_attempt_total 1217
telemt_upstream_connect_success_total 1212
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 1217
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 622
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 589
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 891
telemt_me_reconnect_success_total 886
telemt_me_reader_eof_total 919
telemt_me_idle_close_by_peer_total 919
telemt_me_route_drop_no_conn_total 25296
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 72386
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 232
telemt_desync_full_logged_total 60
telemt_desync_suppressed_total 172
telemt_desync_frames_bucket_total{bucket="1_2"} 64
telemt_desync_frames_bucket_total{bucket="3_10"} 84
telemt_desync_frames_bucket_total{bucket="gt_10"} 84
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 899
telemt_me_writer_restored_same_endpoint_total 875
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 72379
telemt_user_connections_current{user="hello"} 697
telemt_user_octets_from_client{user="hello"} 858637056 (818.86 MB)
telemt_user_octets_to_client{user="hello"} 28259465804 (26.32 GB)
telemt_user_unique_ips_current{user="hello"} 246
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 5627.6 (1h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31098
telemt_connections_bad_total 4441
telemt_handshake_timeouts_total 1900
telemt_upstream_connect_attempt_total 1925
telemt_upstream_connect_success_total 1912
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 1925
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1107
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 777
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_reconnect_attempts_total 1286
telemt_me_reconnect_success_total 1275
telemt_me_reader_eof_total 1298
telemt_me_idle_close_by_peer_total 1298
telemt_me_route_drop_no_conn_total 6146
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 23524
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 75
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 57
telemt_desync_frames_bucket_total{bucket="1_2"} 38
telemt_desync_frames_bucket_total{bucket="3_10"} 18
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1239
telemt_me_writer_restored_same_endpoint_total 1267
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 23821
telemt_user_connections_current{user="hello"} 209
telemt_user_octets_from_client{user="hello"} 1268093895 (1.18 GB)
telemt_user_octets_to_client{user="hello"} 5747740128 (5.35 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 5627.8 (1h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 51606
telemt_connections_bad_total 1013
telemt_handshake_timeouts_total 3211
telemt_upstream_connect_attempt_total 1258
telemt_upstream_connect_success_total 1250
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1258
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 709
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 533
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 925
telemt_me_reconnect_success_total 922
telemt_me_reader_eof_total 955
telemt_me_idle_close_by_peer_total 955
telemt_me_route_drop_no_conn_total 12700
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 46748
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 89
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 59
telemt_desync_frames_bucket_total{bucket="1_2"} 22
telemt_desync_frames_bucket_total{bucket="3_10"} 37
telemt_desync_frames_bucket_total{bucket="gt_10"} 30
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 931
telemt_me_writer_restored_same_endpoint_total 903
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 46668
telemt_user_connections_current{user="hello"} 339
telemt_user_octets_from_client{user="hello"} 660219372 (629.63 MB)
telemt_user_octets_to_client{user="hello"} 14597388800 (13.59 GB)
telemt_user_unique_ips_current{user="hello"} 135
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 5627.6 (1h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 37519
telemt_connections_bad_total 4940
telemt_handshake_timeouts_total 857
telemt_upstream_connect_attempt_total 1979
telemt_upstream_connect_success_total 1916
telemt_upstream_connect_fail_total 63
telemt_upstream_connect_attempts_per_request{bucket="1"} 1979
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 850
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1065
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 63
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 2886
telemt_me_reconnect_success_total 1583
telemt_me_reader_eof_total 1631
telemt_me_idle_close_by_peer_total 1631
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 7783
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 31120
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 55
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 42
telemt_desync_frames_bucket_total{bucket="1_2"} 30
telemt_desync_frames_bucket_total{bucket="3_10"} 24
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 1633
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 1570
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 31122
telemt_user_connections_current{user="hello"} 235
telemt_user_octets_from_client{user="hello"} 219906448 (209.72 MB)
telemt_user_octets_to_client{user="hello"} 8079083392 (7.52 GB)
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 5628.6 (1h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28302
telemt_connections_bad_total 21
telemt_handshake_timeouts_total 527
telemt_upstream_connect_attempt_total 1159
telemt_upstream_connect_success_total 1155
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 1159
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 485
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 666
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 833
telemt_me_reconnect_success_total 827
telemt_me_reader_eof_total 860
telemt_me_idle_close_by_peer_total 860
telemt_me_route_drop_no_conn_total 6876
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 27101
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 140
telemt_desync_full_logged_total 39
telemt_desync_suppressed_total 101
telemt_desync_frames_bucket_total{bucket="1_2"} 50
telemt_desync_frames_bucket_total{bucket="3_10"} 62
telemt_desync_frames_bucket_total{bucket="gt_10"} 28
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 838
telemt_me_writer_restored_same_endpoint_total 819
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 27101
telemt_user_connections_current{user="hello"} 292
telemt_user_octets_from_client{user="hello"} 204072212 (194.62 MB)
telemt_user_octets_to_client{user="hello"} 13944448748 (12.99 GB)
telemt_user_unique_ips_current{user="hello"} 106
telemt_user_unique_ips_recent_window{user="hello"} 33
```