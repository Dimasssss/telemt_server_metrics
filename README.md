# Server Metrics 2026-03-12 08:37:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 9553.2 (2h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 292934
telemt_connections_bad_total 1317
telemt_handshake_timeouts_total 2104
telemt_upstream_connect_attempt_total 1860
telemt_upstream_connect_success_total 1849
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 1860
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1005
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 843
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 1348
telemt_me_reconnect_success_total 1340
telemt_me_reader_eof_total 1385
telemt_me_idle_close_by_peer_total 1385
telemt_me_route_drop_no_conn_total 98327
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 282900
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1358
telemt_desync_full_logged_total 337
telemt_desync_suppressed_total 1021
telemt_desync_frames_bucket_total{bucket="1_2"} 333
telemt_desync_frames_bucket_total{bucket="3_10"} 492
telemt_desync_frames_bucket_total{bucket="gt_10"} 533
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1347
telemt_me_writer_restored_same_endpoint_total 1327
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 282803
telemt_user_connections_current{user="hello"} 1297
telemt_user_octets_from_client{user="hello"} 4318955060 (4.02 GB)
telemt_user_octets_to_client{user="hello"} 79207478284 (73.77 GB)
telemt_user_unique_ips_current{user="hello"} 373
telemt_user_unique_ips_recent_window{user="hello"} 181
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 39173.7 (10h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 213463
telemt_connections_bad_total 2700
telemt_handshake_timeouts_total 7392
telemt_upstream_connect_attempt_total 10104
telemt_upstream_connect_success_total 10098
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 10104
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4966
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5117
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 610
telemt_me_reconnect_attempts_total 7993
telemt_me_reconnect_success_total 7951
telemt_me_reader_eof_total 8445
telemt_me_idle_close_by_peer_total 8445
telemt_me_route_drop_no_conn_total 61627
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 187012
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 447
telemt_desync_full_logged_total 182
telemt_desync_suppressed_total 265
telemt_desync_frames_bucket_total{bucket="1_2"} 127
telemt_desync_frames_bucket_total{bucket="3_10"} 165
telemt_desync_frames_bucket_total{bucket="gt_10"} 155
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 8013
telemt_me_writer_restored_same_endpoint_total 7942
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 187311
telemt_user_connections_current{user="hello"} 546
telemt_user_octets_from_client{user="hello"} 2836898939 (2.64 GB)
telemt_user_octets_to_client{user="hello"} 73134656398 (68.11 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 145
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 39173.4 (10h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 608139
telemt_connections_bad_total 2703
telemt_handshake_timeouts_total 45108
telemt_upstream_connect_attempt_total 10203
telemt_upstream_connect_success_total 10198
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 10203
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5698
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4453
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 508
telemt_me_reconnect_attempts_total 7948
telemt_me_reconnect_success_total 7878
telemt_me_reader_eof_total 8271
telemt_me_idle_close_by_peer_total 8271
telemt_me_route_drop_no_conn_total 121511
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 350811
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1637
telemt_desync_full_logged_total 494
telemt_desync_suppressed_total 1143
telemt_desync_frames_bucket_total{bucket="1_2"} 218
telemt_desync_frames_bucket_total{bucket="3_10"} 565
telemt_desync_frames_bucket_total{bucket="gt_10"} 854
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 7873
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 7837
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 351081
telemt_user_connections_current{user="hello"} 731
telemt_user_octets_from_client{user="hello"} 4232089984 (3.94 GB)
telemt_user_octets_to_client{user="hello"} 119965221317 (111.73 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 217
telemt_user_unique_ips_recent_window{user="hello"} 111
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 39173.9 (10h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 290735
telemt_connections_bad_total 1806
telemt_handshake_timeouts_total 19510
telemt_upstream_connect_attempt_total 10807
telemt_upstream_connect_success_total 10764
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 10807
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6159
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4596
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 772
telemt_me_reconnect_attempts_total 8832
telemt_me_reconnect_success_total 8800
telemt_me_reader_eof_total 9344
telemt_me_idle_close_by_peer_total 9344
telemt_me_route_drop_no_conn_total 97250
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 242672
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 464
telemt_desync_full_logged_total 168
telemt_desync_suppressed_total 296
telemt_desync_frames_bucket_total{bucket="1_2"} 151
telemt_desync_frames_bucket_total{bucket="3_10"} 185
telemt_desync_frames_bucket_total{bucket="gt_10"} 128
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 8855
telemt_me_writer_restored_same_endpoint_total 8779
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 242497
telemt_user_connections_current{user="hello"} 499
telemt_user_octets_from_client{user="hello"} 2841321328 (2.65 GB)
telemt_user_octets_to_client{user="hello"} 83868482468 (78.11 GB)
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 39173.8 (10h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 322328
telemt_connections_bad_total 372
telemt_handshake_timeouts_total 2476
telemt_upstream_connect_attempt_total 13017
telemt_upstream_connect_success_total 12865
telemt_upstream_connect_fail_total 152
telemt_upstream_connect_attempts_per_request{bucket="1"} 13017
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6631
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6158
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 152
telemt_me_keepalive_timeout_total 562
telemt_me_reconnect_attempts_total 12406
telemt_me_reconnect_success_total 10892
telemt_me_reader_eof_total 11348
telemt_me_idle_close_by_peer_total 11348
telemt_me_seq_mismatch_total 16
telemt_me_route_drop_no_conn_total 103139
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 303999
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1242
telemt_desync_full_logged_total 416
telemt_desync_suppressed_total 826
telemt_desync_frames_bucket_total{bucket="1_2"} 324
telemt_desync_frames_bucket_total{bucket="3_10"} 442
telemt_desync_frames_bucket_total{bucket="gt_10"} 476
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 11038
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 10871
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 146
telemt_user_connections_total{user="hello"} 303941
telemt_user_connections_current{user="hello"} 770
telemt_user_octets_from_client{user="hello"} 3238638848 (3.02 GB)
telemt_user_octets_to_client{user="hello"} 72749881684 (67.75 GB)
telemt_user_unique_ips_current{user="hello"} 190
telemt_user_unique_ips_recent_window{user="hello"} 101
```