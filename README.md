# Server Metrics 2026-03-11 14:36:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 86946.1 (24h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2101584
telemt_connections_bad_total 32591
telemt_handshake_timeouts_total 52139
telemt_upstream_connect_attempt_total 18370
telemt_upstream_connect_success_total 18358
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 18370
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9264
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9004
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 4849
telemt_me_reconnect_attempts_total 29199
telemt_me_reconnect_success_total 13957
telemt_me_reader_eof_total 15085
telemt_me_idle_close_by_peer_total 15085
telemt_me_route_drop_no_conn_total 776423
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1921878
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10094
telemt_desync_full_logged_total 2733
telemt_desync_suppressed_total 7361
telemt_desync_frames_bucket_total{bucket="1_2"} 2509
telemt_desync_frames_bucket_total{bucket="3_10"} 3894
telemt_desync_frames_bucket_total{bucket="gt_10"} 3691
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 14584
telemt_me_refill_failed_total 473
telemt_me_writer_restored_same_endpoint_total 13951
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 627
telemt_user_connections_total{user="hello"} 1920384
telemt_user_connections_current{user="hello"} 1679
telemt_user_octets_from_client{user="hello"} 25867518040 (24.09 GB)
telemt_user_octets_to_client{user="hello"} 548459709980 (510.79 GB)
telemt_user_unique_ips_current{user="hello"} 410
telemt_user_unique_ips_recent_window{user="hello"} 209
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 87002.8 (24h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 787233
telemt_connections_bad_total 13168
telemt_handshake_timeouts_total 53351
telemt_upstream_connect_attempt_total 27795
telemt_upstream_connect_success_total 24846
telemt_upstream_connect_fail_total 2949
telemt_upstream_connect_attempts_per_request{bucket="1"} 27795
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11499
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11099
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2039
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2949
telemt_me_keepalive_timeout_total 2524
telemt_me_reconnect_attempts_total 19624
telemt_me_reconnect_success_total 17535
telemt_me_reader_eof_total 18571
telemt_me_idle_close_by_peer_total 18568
telemt_me_route_drop_no_conn_total 308404
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 667219
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2840
telemt_desync_full_logged_total 901
telemt_desync_suppressed_total 1939
telemt_desync_frames_bucket_total{bucket="1_2"} 881
telemt_desync_frames_bucket_total{bucket="3_10"} 1030
telemt_desync_frames_bucket_total{bucket="gt_10"} 929
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 17793
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 17512
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 258
telemt_user_connections_total{user="hello"} 669696
telemt_user_connections_current{user="hello"} 583
telemt_user_octets_from_client{user="hello"} 7110371318 (6.62 GB)
telemt_user_octets_to_client{user="hello"} 189527765380 (176.51 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 170
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 87002.8 (24h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1363743
telemt_connections_bad_total 8455
telemt_handshake_timeouts_total 122235
telemt_upstream_connect_attempt_total 23101
telemt_upstream_connect_success_total 22827
telemt_upstream_connect_fail_total 274
telemt_upstream_connect_attempts_per_request{bucket="1"} 23101
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12320
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10390
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 117
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 274
telemt_me_keepalive_timeout_total 1554
telemt_me_reconnect_attempts_total 33483
telemt_me_reconnect_success_total 17371
telemt_me_reader_eof_total 18668
telemt_me_idle_close_by_peer_total 18668
telemt_me_route_drop_no_conn_total 493249
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1182227
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3147
telemt_desync_full_logged_total 928
telemt_desync_suppressed_total 2219
telemt_desync_frames_bucket_total{bucket="1_2"} 764
telemt_desync_frames_bucket_total{bucket="3_10"} 1193
telemt_desync_frames_bucket_total{bucket="gt_10"} 1190
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 18109
telemt_me_refill_failed_total 499
telemt_me_writer_restored_same_endpoint_total 17360
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 738
telemt_user_connections_total{user="hello"} 1181996
telemt_user_connections_current{user="hello"} 848
telemt_user_octets_from_client{user="hello"} 14204009929 (13.23 GB)
telemt_user_octets_to_client{user="hello"} 352687150909 (328.47 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 239
telemt_user_unique_ips_recent_window{user="hello"} 130
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 87003.2 (24h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 979331
telemt_connections_bad_total 77575
telemt_handshake_timeouts_total 93753
telemt_upstream_connect_attempt_total 23477
telemt_upstream_connect_success_total 23477
telemt_upstream_connect_attempts_per_request{bucket="1"} 23477
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12848
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10624
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 962
telemt_me_reconnect_attempts_total 20208
telemt_me_reconnect_success_total 19134
telemt_me_reader_eof_total 20293
telemt_me_idle_close_by_peer_total 20292
telemt_me_seq_mismatch_total 17
telemt_me_route_drop_no_conn_total 318337
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 781456
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 28
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1655
telemt_desync_full_logged_total 644
telemt_desync_suppressed_total 1011
telemt_desync_frames_bucket_total{bucket="1_2"} 597
telemt_desync_frames_bucket_total{bucket="3_10"} 580
telemt_desync_frames_bucket_total{bucket="gt_10"} 478
telemt_pool_swap_total 76
telemt_me_writer_removed_unexpected_total 19371
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 19106
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 237
telemt_user_connections_total{user="hello"} 780789
telemt_user_connections_current{user="hello"} 603
telemt_user_octets_from_client{user="hello"} 9149944780 (8.52 GB)
telemt_user_octets_to_client{user="hello"} 228182609304 (212.51 GB)
telemt_user_unique_ips_current{user="hello"} 171
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 87002.8 (24h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1076696
telemt_connections_bad_total 6936
telemt_handshake_timeouts_total 10753
telemt_upstream_connect_attempt_total 23596
telemt_upstream_connect_success_total 23491
telemt_upstream_connect_fail_total 105
telemt_upstream_connect_attempts_per_request{bucket="1"} 23596
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12016
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11277
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 193
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 105
telemt_me_keepalive_timeout_total 1842
telemt_me_reconnect_attempts_total 23098
telemt_me_reconnect_success_total 19014
telemt_me_reader_eof_total 20046
telemt_me_idle_close_by_peer_total 20046
telemt_me_route_drop_no_conn_total 382049
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 978015
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3819
telemt_desync_full_logged_total 1400
telemt_desync_suppressed_total 2419
telemt_desync_frames_bucket_total{bucket="1_2"} 1333
telemt_desync_frames_bucket_total{bucket="3_10"} 1438
telemt_desync_frames_bucket_total{bucket="gt_10"} 1048
telemt_pool_swap_total 58
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 19388
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 19014
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 374
telemt_user_connections_total{user="hello"} 977744
telemt_user_connections_current{user="hello"} 789
telemt_user_octets_from_client{user="hello"} 14106227487 (13.14 GB)
telemt_user_octets_to_client{user="hello"} 343062641654 (319.50 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 207
telemt_user_unique_ips_recent_window{user="hello"} 121
```