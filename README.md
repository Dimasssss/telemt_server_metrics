# Server Metrics 2026-03-13 21:58:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 143994.0 (39h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4505913
telemt_connections_bad_total 38143
telemt_handshake_timeouts_total 106803
telemt_upstream_connect_attempt_total 30046
telemt_upstream_connect_success_total 29838
telemt_upstream_connect_fail_total 208
telemt_upstream_connect_attempts_per_request{bucket="1"} 30046
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16386
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13308
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 144
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 208
telemt_me_keepalive_timeout_total 6622
telemt_me_reconnect_attempts_total 30463
telemt_me_reconnect_success_total 20343
telemt_me_reader_eof_total 21826
telemt_me_idle_close_by_peer_total 21825
telemt_me_route_drop_no_conn_total 1700705
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4128658
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16455
telemt_desync_full_logged_total 4412
telemt_desync_suppressed_total 12043
telemt_desync_frames_bucket_total{bucket="1_2"} 4098
telemt_desync_frames_bucket_total{bucket="3_10"} 6287
telemt_desync_frames_bucket_total{bucket="gt_10"} 6070
telemt_pool_swap_total 122
telemt_me_writer_removed_unexpected_total 20953
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 20330
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 610
telemt_user_connections_total{user="hello"} 4130787
telemt_user_connections_current{user="hello"} 780
telemt_user_octets_from_client{user="hello"} 60748561392 (56.58 GB)
telemt_user_octets_to_client{user="hello"} 1307809864561 (1.19 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 252
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 43657.8 (12h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 583108
telemt_connections_bad_total 41513
telemt_handshake_timeouts_total 12370
telemt_upstream_connect_attempt_total 12357
telemt_upstream_connect_success_total 12133
telemt_upstream_connect_fail_total 224
telemt_upstream_connect_attempts_per_request{bucket="1"} 12357
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7031
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4880
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 21
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 201
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 224
telemt_me_keepalive_timeout_total 1902
telemt_me_reconnect_attempts_total 11334
telemt_me_reconnect_success_total 7906
telemt_me_reader_eof_total 8371
telemt_me_idle_close_by_peer_total 8370
telemt_me_route_drop_no_conn_total 213385
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 506000
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1643
telemt_desync_full_logged_total 444
telemt_desync_suppressed_total 1199
telemt_desync_frames_bucket_total{bucket="1_2"} 348
telemt_desync_frames_bucket_total{bucket="3_10"} 712
telemt_desync_frames_bucket_total{bucket="gt_10"} 583
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 8126
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 7898
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 220
telemt_user_connections_total{user="hello"} 507931
telemt_user_connections_current{user="hello"} 293
telemt_user_octets_from_client{user="hello"} 5522768853 (5.14 GB)
telemt_user_octets_to_client{user="hello"} 166011334604 (154.61 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 102
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 173614.5 (48h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3277477
telemt_connections_bad_total 31403
telemt_handshake_timeouts_total 219582
telemt_upstream_connect_attempt_total 38477
telemt_upstream_connect_success_total 38456
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 38477
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20059
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18173
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 217
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10272
telemt_me_reconnect_attempts_total 34453
telemt_me_reconnect_success_total 29503
telemt_me_reader_eof_total 31309
telemt_me_idle_close_by_peer_total 31308
telemt_me_route_drop_no_conn_total 1122193
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2720093
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8929
telemt_desync_full_logged_total 2999
telemt_desync_suppressed_total 5930
telemt_desync_frames_bucket_total{bucket="1_2"} 1470
telemt_desync_frames_bucket_total{bucket="3_10"} 3251
telemt_desync_frames_bucket_total{bucket="gt_10"} 4208
telemt_pool_swap_total 160
telemt_me_writer_removed_unexpected_total 29939
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 29462
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 436
telemt_user_connections_total{user="hello"} 2719358
telemt_user_connections_current{user="hello"} 495
telemt_user_octets_from_client{user="hello"} 44471225440 (41.42 GB)
telemt_user_octets_to_client{user="hello"} 960232200349 (894.29 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 159
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 173617.2 (48h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2135095
telemt_connections_bad_total 22813
telemt_handshake_timeouts_total 213094
telemt_upstream_connect_attempt_total 53999
telemt_upstream_connect_success_total 51554
telemt_upstream_connect_fail_total 2308
telemt_upstream_connect_attempts_per_request{bucket="1"} 53725
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30895
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20493
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2307
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20306
telemt_me_reconnect_attempts_total 44912
telemt_me_reconnect_success_total 35897
telemt_me_reader_eof_total 38500
telemt_me_idle_close_by_peer_total 38493
telemt_me_route_drop_no_conn_total 751174
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1748996
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3790
telemt_desync_full_logged_total 1212
telemt_desync_suppressed_total 2578
telemt_desync_frames_bucket_total{bucket="1_2"} 999
telemt_desync_frames_bucket_total{bucket="3_10"} 1585
telemt_desync_frames_bucket_total{bucket="gt_10"} 1206
telemt_pool_swap_total 151
telemt_me_writer_removed_unexpected_total 36489
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 35873
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 592
telemt_user_connections_total{user="hello"} 1754877
telemt_user_connections_current{user="hello"} 330
telemt_user_octets_from_client{user="hello"} 27246457475 (25.38 GB)
telemt_user_octets_to_client{user="hello"} 656297571202 (611.22 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 114
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 43050.6 (11h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 622744
telemt_connections_bad_total 5845
telemt_handshake_timeouts_total 5711
telemt_upstream_connect_attempt_total 9742
telemt_upstream_connect_success_total 9427
telemt_upstream_connect_fail_total 315
telemt_upstream_connect_attempts_per_request{bucket="1"} 9742
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4542
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4864
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 315
telemt_me_keepalive_timeout_total 979
telemt_me_reconnect_attempts_total 33176
telemt_me_reconnect_success_total 7275
telemt_me_reader_eof_total 8216
telemt_me_idle_close_by_peer_total 8215
telemt_me_route_drop_no_conn_total 237217
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 583400
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1544
telemt_desync_full_logged_total 483
telemt_desync_suppressed_total 1061
telemt_desync_frames_bucket_total{bucket="1_2"} 469
telemt_desync_frames_bucket_total{bucket="3_10"} 605
telemt_desync_frames_bucket_total{bucket="gt_10"} 470
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 8146
telemt_me_refill_failed_total 806
telemt_me_writer_restored_same_endpoint_total 7270
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 871
telemt_user_connections_total{user="hello"} 583312
telemt_user_connections_current{user="hello"} 382
telemt_user_octets_from_client{user="hello"} 8570593884 (7.98 GB)
telemt_user_octets_to_client{user="hello"} 186218454480 (173.43 GB)
telemt_user_unique_ips_current{user="hello"} 119
telemt_user_unique_ips_recent_window{user="hello"} 37
```