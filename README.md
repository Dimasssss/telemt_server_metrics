# Server Metrics 2026-03-11 19:17:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 103795.9 (28h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2637519
telemt_connections_bad_total 48650
telemt_handshake_timeouts_total 57771
telemt_upstream_connect_attempt_total 21908
telemt_upstream_connect_success_total 21896
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 21908
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11080
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10706
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 5333
telemt_me_reconnect_attempts_total 34516
telemt_me_reconnect_success_total 16626
telemt_me_reader_eof_total 17978
telemt_me_idle_close_by_peer_total 17978
telemt_me_route_drop_no_conn_total 994868
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2411350
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12240
telemt_desync_full_logged_total 3391
telemt_desync_suppressed_total 8849
telemt_desync_frames_bucket_total{bucket="1_2"} 2998
telemt_desync_frames_bucket_total{bucket="3_10"} 4731
telemt_desync_frames_bucket_total{bucket="gt_10"} 4511
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 17371
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 16620
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 745
telemt_user_connections_total{user="hello"} 2409700
telemt_user_connections_current{user="hello"} 1192
telemt_user_octets_from_client{user="hello"} 36011379616 (33.54 GB)
telemt_user_octets_to_client{user="hello"} 683954609848 (636.98 GB)
telemt_user_unique_ips_current{user="hello"} 342
telemt_user_unique_ips_recent_window{user="hello"} 171
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 103852.2 (28h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 982680
telemt_connections_bad_total 16437
telemt_handshake_timeouts_total 88332
telemt_upstream_connect_attempt_total 32119
telemt_upstream_connect_success_total 29149
telemt_upstream_connect_fail_total 2970
telemt_upstream_connect_attempts_per_request{bucket="1"} 32119
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13756
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13133
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2051
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2970
telemt_me_keepalive_timeout_total 2850
telemt_me_reconnect_attempts_total 23082
telemt_me_reconnect_success_total 20966
telemt_me_reader_eof_total 22199
telemt_me_idle_close_by_peer_total 22196
telemt_me_route_drop_no_conn_total 371392
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 819692
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3236
telemt_desync_full_logged_total 1052
telemt_desync_suppressed_total 2184
telemt_desync_frames_bucket_total{bucket="1_2"} 1027
telemt_desync_frames_bucket_total{bucket="3_10"} 1153
telemt_desync_frames_bucket_total{bucket="gt_10"} 1056
telemt_pool_swap_total 84
telemt_me_writer_removed_unexpected_total 21261
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 20943
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 295
telemt_user_connections_total{user="hello"} 822139
telemt_user_connections_current{user="hello"} 369
telemt_user_octets_from_client{user="hello"} 9861062002 (9.18 GB)
telemt_user_octets_to_client{user="hello"} 237405452604 (221.10 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 118
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 103852.3 (28h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1691479
telemt_connections_bad_total 10606
telemt_handshake_timeouts_total 133730
telemt_upstream_connect_attempt_total 26854
telemt_upstream_connect_success_total 26518
telemt_upstream_connect_fail_total 336
telemt_upstream_connect_attempts_per_request{bucket="1"} 26854
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14324
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12058
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 135
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 336
telemt_me_keepalive_timeout_total 1985
telemt_me_reconnect_attempts_total 51184
telemt_me_reconnect_success_total 20185
telemt_me_reader_eof_total 22013
telemt_me_idle_close_by_peer_total 22013
telemt_me_route_drop_no_conn_total 616776
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1483130
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4105
telemt_desync_full_logged_total 1206
telemt_desync_suppressed_total 2899
telemt_desync_frames_bucket_total{bucket="1_2"} 957
telemt_desync_frames_bucket_total{bucket="3_10"} 1557
telemt_desync_frames_bucket_total{bucket="gt_10"} 1591
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 21433
telemt_me_refill_failed_total 963
telemt_me_writer_restored_same_endpoint_total 20173
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 1248
telemt_user_connections_total{user="hello"} 1482797
telemt_user_connections_current{user="hello"} 692
telemt_user_octets_from_client{user="hello"} 19193141933 (17.88 GB)
telemt_user_octets_to_client{user="hello"} 452103019961 (421.05 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 211
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 103852.7 (28h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1209363
telemt_connections_bad_total 78201
telemt_handshake_timeouts_total 110561
telemt_upstream_connect_attempt_total 28105
telemt_upstream_connect_success_total 28105
telemt_upstream_connect_attempts_per_request{bucket="1"} 28105
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15325
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12774
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1437
telemt_me_reconnect_attempts_total 27512
telemt_me_reconnect_success_total 22898
telemt_me_reader_eof_total 24312
telemt_me_idle_close_by_peer_total 24311
telemt_me_seq_mismatch_total 23
telemt_me_route_drop_no_conn_total 403980
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 985634
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2101
telemt_desync_full_logged_total 797
telemt_desync_suppressed_total 1304
telemt_desync_frames_bucket_total{bucket="1_2"} 758
telemt_desync_frames_bucket_total{bucket="3_10"} 715
telemt_desync_frames_bucket_total{bucket="gt_10"} 628
telemt_pool_swap_total 84
telemt_me_writer_removed_unexpected_total 23283
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 22865
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 385
telemt_user_connections_total{user="hello"} 984894
telemt_user_connections_current{user="hello"} 446
telemt_user_octets_from_client{user="hello"} 11686198180 (10.88 GB)
telemt_user_octets_to_client{user="hello"} 298626363096 (278.12 GB)
telemt_user_unique_ips_current{user="hello"} 143
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 8528.7 (2h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 135369
telemt_connections_bad_total 642
telemt_handshake_timeouts_total 840
telemt_upstream_connect_attempt_total 2508
telemt_upstream_connect_success_total 2507
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2508
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1314
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1178
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 2039
telemt_me_reconnect_success_total 2019
telemt_me_reader_eof_total 2056
telemt_me_idle_close_by_peer_total 2056
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 47449
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 124767
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 240
telemt_desync_full_logged_total 80
telemt_desync_suppressed_total 160
telemt_desync_frames_bucket_total{bucket="1_2"} 61
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 97
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 2044
telemt_me_writer_restored_same_endpoint_total 1995
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 256
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 124734
telemt_user_connections_current{user="hello"} 634
telemt_user_octets_from_client{user="hello"} 6556622384 (6.11 GB)
telemt_user_octets_to_client{user="hello"} 42011231512 (39.13 GB)
telemt_user_unique_ips_current{user="hello"} 159
telemt_user_unique_ips_recent_window{user="hello"} 81
```