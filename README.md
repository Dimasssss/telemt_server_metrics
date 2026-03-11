# Server Metrics 2026-03-11 19:27:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 104406.9 (29h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2652678
telemt_connections_bad_total 48652
telemt_handshake_timeouts_total 58278
telemt_upstream_connect_attempt_total 21955
telemt_upstream_connect_success_total 21943
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 21955
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11096
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10737
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 5344
telemt_me_reconnect_attempts_total 34563
telemt_me_reconnect_success_total 16673
telemt_me_reader_eof_total 18027
telemt_me_idle_close_by_peer_total 18027
telemt_me_route_drop_no_conn_total 1001414
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2424613
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12309
telemt_desync_full_logged_total 3410
telemt_desync_suppressed_total 8899
telemt_desync_frames_bucket_total{bucket="1_2"} 3013
telemt_desync_frames_bucket_total{bucket="3_10"} 4757
telemt_desync_frames_bucket_total{bucket="gt_10"} 4539
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 17420
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 16667
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 747
telemt_user_connections_total{user="hello"} 2422966
telemt_user_connections_current{user="hello"} 1027
telemt_user_octets_from_client{user="hello"} 36261673528 (33.77 GB)
telemt_user_octets_to_client{user="hello"} 687246105488 (640.05 GB)
telemt_user_unique_ips_current{user="hello"} 321
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 104463.5 (29h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 987069
telemt_connections_bad_total 16464
telemt_handshake_timeouts_total 88831
telemt_upstream_connect_attempt_total 32211
telemt_upstream_connect_success_total 29240
telemt_upstream_connect_fail_total 2971
telemt_upstream_connect_attempts_per_request{bucket="1"} 32211
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13802
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13173
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2056
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2971
telemt_me_keepalive_timeout_total 2853
telemt_me_reconnect_attempts_total 23150
telemt_me_reconnect_success_total 21034
telemt_me_reader_eof_total 22271
telemt_me_idle_close_by_peer_total 22268
telemt_me_route_drop_no_conn_total 372943
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 823399
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3253
telemt_desync_full_logged_total 1058
telemt_desync_suppressed_total 2195
telemt_desync_frames_bucket_total{bucket="1_2"} 1032
telemt_desync_frames_bucket_total{bucket="3_10"} 1159
telemt_desync_frames_bucket_total{bucket="gt_10"} 1062
telemt_pool_swap_total 84
telemt_me_writer_removed_unexpected_total 21333
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 21011
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 299
telemt_user_connections_total{user="hello"} 825845
telemt_user_connections_current{user="hello"} 405
telemt_user_octets_from_client{user="hello"} 9909072578 (9.23 GB)
telemt_user_octets_to_client{user="hello"} 238717917952 (222.32 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 125
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 104463.5 (29h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1700735
telemt_connections_bad_total 10609
telemt_handshake_timeouts_total 133933
telemt_upstream_connect_attempt_total 26934
telemt_upstream_connect_success_total 26598
telemt_upstream_connect_fail_total 336
telemt_upstream_connect_attempts_per_request{bucket="1"} 26934
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14378
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12084
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 135
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 336
telemt_me_keepalive_timeout_total 1985
telemt_me_reconnect_attempts_total 51251
telemt_me_reconnect_success_total 20252
telemt_me_reader_eof_total 22080
telemt_me_idle_close_by_peer_total 22080
telemt_me_route_drop_no_conn_total 620031
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1491899
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4111
telemt_desync_full_logged_total 1210
telemt_desync_suppressed_total 2901
telemt_desync_frames_bucket_total{bucket="1_2"} 959
telemt_desync_frames_bucket_total{bucket="3_10"} 1560
telemt_desync_frames_bucket_total{bucket="gt_10"} 1592
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 21500
telemt_me_refill_failed_total 963
telemt_me_writer_restored_same_endpoint_total 20240
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 1248
telemt_user_connections_total{user="hello"} 1491553
telemt_user_connections_current{user="hello"} 643
telemt_user_octets_from_client{user="hello"} 19267026693 (17.94 GB)
telemt_user_octets_to_client{user="hello"} 454828830461 (423.59 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 215
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 104464.0 (29h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1215848
telemt_connections_bad_total 78201
telemt_handshake_timeouts_total 110649
telemt_upstream_connect_attempt_total 28221
telemt_upstream_connect_success_total 28221
telemt_upstream_connect_attempts_per_request{bucket="1"} 28221
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15390
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12825
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1439
telemt_me_reconnect_attempts_total 27602
telemt_me_reconnect_success_total 22987
telemt_me_reader_eof_total 24401
telemt_me_idle_close_by_peer_total 24400
telemt_me_seq_mismatch_total 23
telemt_me_route_drop_no_conn_total 406212
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 991925
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2135
telemt_desync_full_logged_total 803
telemt_desync_suppressed_total 1332
telemt_desync_frames_bucket_total{bucket="1_2"} 762
telemt_desync_frames_bucket_total{bucket="3_10"} 725
telemt_desync_frames_bucket_total{bucket="gt_10"} 648
telemt_pool_swap_total 84
telemt_me_writer_removed_unexpected_total 23372
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 22954
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 385
telemt_user_connections_total{user="hello"} 991137
telemt_user_connections_current{user="hello"} 496
telemt_user_octets_from_client{user="hello"} 11751856160 (10.94 GB)
telemt_user_octets_to_client{user="hello"} 300321265788 (279.70 GB)
telemt_user_unique_ips_current{user="hello"} 142
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 9140.2 (2h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 144233
telemt_connections_bad_total 753
telemt_handshake_timeouts_total 1048
telemt_upstream_connect_attempt_total 2757
telemt_upstream_connect_success_total 2756
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2757
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1429
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1312
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 2245
telemt_me_reconnect_success_total 2225
telemt_me_reader_eof_total 2274
telemt_me_idle_close_by_peer_total 2274
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 50293
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 132518
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 256
telemt_desync_full_logged_total 82
telemt_desync_suppressed_total 174
telemt_desync_frames_bucket_total{bucket="1_2"} 64
telemt_desync_frames_bucket_total{bucket="3_10"} 85
telemt_desync_frames_bucket_total{bucket="gt_10"} 107
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 2250
telemt_me_writer_restored_same_endpoint_total 2200
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 256
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 132485
telemt_user_connections_current{user="hello"} 568
telemt_user_octets_from_client{user="hello"} 6642481900 (6.19 GB)
telemt_user_octets_to_client{user="hello"} 44619123788 (41.55 GB)
telemt_user_unique_ips_current{user="hello"} 142
telemt_user_unique_ips_recent_window{user="hello"} 68
```