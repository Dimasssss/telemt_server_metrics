# Server Metrics 2026-03-14 05:23:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 170679.4 (47h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4826089
telemt_connections_bad_total 40016
telemt_handshake_timeouts_total 110361
telemt_upstream_connect_attempt_total 35934
telemt_upstream_connect_success_total 35699
telemt_upstream_connect_fail_total 235
telemt_upstream_connect_attempts_per_request{bucket="1"} 35934
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19423
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16129
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 147
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 235
telemt_me_keepalive_timeout_total 7304
telemt_me_reconnect_attempts_total 35021
telemt_me_reconnect_success_total 24875
telemt_me_reader_eof_total 26700
telemt_me_idle_close_by_peer_total 26699
telemt_me_route_drop_no_conn_total 1827442
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4428486
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 17055
telemt_desync_full_logged_total 4606
telemt_desync_suppressed_total 12449
telemt_desync_frames_bucket_total{bucket="1_2"} 4261
telemt_desync_frames_bucket_total{bucket="3_10"} 6509
telemt_desync_frames_bucket_total{bucket="gt_10"} 6285
telemt_pool_swap_total 149
telemt_me_writer_removed_unexpected_total 25547
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 24862
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 672
telemt_user_connections_total{user="hello"} 4430036
telemt_user_connections_current{user="hello"} 1079
telemt_user_octets_from_client{user="hello"} 64784097284 (60.33 GB)
telemt_user_octets_to_client{user="hello"} 1398894659709 (1.27 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 326
telemt_user_unique_ips_recent_window{user="hello"} 124
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 70343.3 (19h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 768558
telemt_connections_bad_total 53070
telemt_handshake_timeouts_total 14169
telemt_upstream_connect_attempt_total 19329
telemt_upstream_connect_success_total 19061
telemt_upstream_connect_fail_total 268
telemt_upstream_connect_attempts_per_request{bucket="1"} 19329
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10527
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8279
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 225
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 268
telemt_me_keepalive_timeout_total 2113
telemt_me_reconnect_attempts_total 16966
telemt_me_reconnect_success_total 13508
telemt_me_reader_eof_total 14353
telemt_me_idle_close_by_peer_total 14352
telemt_me_route_drop_no_conn_total 251889
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 607214
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1816
telemt_desync_full_logged_total 538
telemt_desync_suppressed_total 1278
telemt_desync_frames_bucket_total{bucket="1_2"} 381
telemt_desync_frames_bucket_total{bucket="3_10"} 810
telemt_desync_frames_bucket_total{bucket="gt_10"} 625
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 13800
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 13500
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 292
telemt_user_connections_total{user="hello"} 609167
telemt_user_connections_current{user="hello"} 344
telemt_user_octets_from_client{user="hello"} 6485865665 (6.04 GB)
telemt_user_octets_to_client{user="hello"} 206314450736 (192.15 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 200299.9 (55h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3469679
telemt_connections_bad_total 37931
telemt_handshake_timeouts_total 229483
telemt_upstream_connect_attempt_total 45295
telemt_upstream_connect_success_total 45274
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 45295
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23832
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21195
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 240
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10630
telemt_me_reconnect_attempts_total 39971
telemt_me_reconnect_success_total 35001
telemt_me_reader_eof_total 37181
telemt_me_idle_close_by_peer_total 37180
telemt_me_route_drop_no_conn_total 1185850
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2890085
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9557
telemt_desync_full_logged_total 3211
telemt_desync_suppressed_total 6346
telemt_desync_frames_bucket_total{bucket="1_2"} 1658
telemt_desync_frames_bucket_total{bucket="3_10"} 3464
telemt_desync_frames_bucket_total{bucket="gt_10"} 4435
telemt_pool_swap_total 190
telemt_me_writer_removed_unexpected_total 35486
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 34960
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 485
telemt_user_connections_total{user="hello"} 2889298
telemt_user_connections_current{user="hello"} 589
telemt_user_octets_from_client{user="hello"} 46294986584 (43.12 GB)
telemt_user_octets_to_client{user="hello"} 1035923935885 (964.78 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 206
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 200302.5 (55h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2324519
telemt_connections_bad_total 23128
telemt_handshake_timeouts_total 265626
telemt_upstream_connect_attempt_total 62597
telemt_upstream_connect_success_total 60118
telemt_upstream_connect_fail_total 2342
telemt_upstream_connect_attempts_per_request{bucket="1"} 62323
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35913
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24039
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2341
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20472
telemt_me_reconnect_attempts_total 52172
telemt_me_reconnect_success_total 43130
telemt_me_reader_eof_total 46245
telemt_me_idle_close_by_peer_total 46238
telemt_me_route_drop_no_conn_total 787449
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1841250
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3886
telemt_desync_full_logged_total 1253
telemt_desync_suppressed_total 2633
telemt_desync_frames_bucket_total{bucket="1_2"} 1045
telemt_desync_frames_bucket_total{bucket="3_10"} 1615
telemt_desync_frames_bucket_total{bucket="gt_10"} 1226
telemt_pool_swap_total 177
telemt_me_writer_removed_unexpected_total 43787
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 43106
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 657
telemt_user_connections_total{user="hello"} 1847232
telemt_user_connections_current{user="hello"} 311
telemt_user_octets_from_client{user="hello"} 27984023707 (26.06 GB)
telemt_user_octets_to_client{user="hello"} 676788532706 (630.31 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 106
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 69736.2 (19h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 749769
telemt_connections_bad_total 8025
telemt_handshake_timeouts_total 8951
telemt_upstream_connect_attempt_total 18130
telemt_upstream_connect_success_total 17655
telemt_upstream_connect_fail_total 475
telemt_upstream_connect_attempts_per_request{bucket="1"} 18130
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8335
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9294
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 475
telemt_me_keepalive_timeout_total 1546
telemt_me_reconnect_attempts_total 54032
telemt_me_reconnect_success_total 14167
telemt_me_reader_eof_total 15767
telemt_me_idle_close_by_peer_total 15766
telemt_me_route_drop_no_conn_total 286704
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 699945
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1751
telemt_desync_full_logged_total 557
telemt_desync_suppressed_total 1194
telemt_desync_frames_bucket_total{bucket="1_2"} 518
telemt_desync_frames_bucket_total{bucket="3_10"} 686
telemt_desync_frames_bucket_total{bucket="gt_10"} 547
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 15537
telemt_me_refill_failed_total 1241
telemt_me_writer_restored_same_endpoint_total 14162
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1370
telemt_user_connections_total{user="hello"} 699810
telemt_user_connections_current{user="hello"} 415
telemt_user_octets_from_client{user="hello"} 12574048720 (11.71 GB)
telemt_user_octets_to_client{user="hello"} 232264621696 (216.31 GB)
telemt_user_unique_ips_current{user="hello"} 134
telemt_user_unique_ips_recent_window{user="hello"} 54
```