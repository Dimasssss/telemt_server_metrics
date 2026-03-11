# Server Metrics 2026-03-11 16:54:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 95218.0 (26h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2380994
telemt_connections_bad_total 41262
telemt_handshake_timeouts_total 54157
telemt_upstream_connect_attempt_total 19906
telemt_upstream_connect_success_total 19894
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 19906
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10029
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9770
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 94
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 5076
telemt_me_reconnect_attempts_total 32957
telemt_me_reconnect_success_total 15082
telemt_me_reader_eof_total 16347
telemt_me_idle_close_by_peer_total 16347
telemt_me_route_drop_no_conn_total 884106
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2179230
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11277
telemt_desync_full_logged_total 3083
telemt_desync_suppressed_total 8194
telemt_desync_frames_bucket_total{bucket="1_2"} 2783
telemt_desync_frames_bucket_total{bucket="3_10"} 4353
telemt_desync_frames_bucket_total{bucket="gt_10"} 4141
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 15808
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 15076
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 726
telemt_user_connections_total{user="hello"} 2177678
telemt_user_connections_current{user="hello"} 1275
telemt_user_octets_from_client{user="hello"} 29274903476 (27.26 GB)
telemt_user_octets_to_client{user="hello"} 614235904672 (572.05 GB)
telemt_user_unique_ips_current{user="hello"} 376
telemt_user_unique_ips_recent_window{user="hello"} 172
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 95274.7 (26h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 895718
telemt_connections_bad_total 15590
telemt_handshake_timeouts_total 76113
telemt_upstream_connect_attempt_total 30056
telemt_upstream_connect_success_total 27096
telemt_upstream_connect_fail_total 2960
telemt_upstream_connect_attempts_per_request{bucket="1"} 30056
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12692
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12155
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2040
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2960
telemt_me_keepalive_timeout_total 2656
telemt_me_reconnect_attempts_total 21469
telemt_me_reconnect_success_total 19368
telemt_me_reader_eof_total 20479
telemt_me_idle_close_by_peer_total 20476
telemt_me_route_drop_no_conn_total 341667
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 748576
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3014
telemt_desync_full_logged_total 960
telemt_desync_suppressed_total 2054
telemt_desync_frames_bucket_total{bucket="1_2"} 913
telemt_desync_frames_bucket_total{bucket="3_10"} 1085
telemt_desync_frames_bucket_total{bucket="gt_10"} 1016
telemt_pool_swap_total 76
telemt_me_writer_removed_unexpected_total 19642
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 19345
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 274
telemt_user_connections_total{user="hello"} 751035
telemt_user_connections_current{user="hello"} 484
telemt_user_octets_from_client{user="hello"} 8614381666 (8.02 GB)
telemt_user_octets_to_client{user="hello"} 212185703176 (197.61 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 95274.7 (26h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1526883
telemt_connections_bad_total 8973
telemt_handshake_timeouts_total 126149
telemt_upstream_connect_attempt_total 24572
telemt_upstream_connect_success_total 24260
telemt_upstream_connect_fail_total 312
telemt_upstream_connect_attempts_per_request{bucket="1"} 24572
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13087
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11048
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 125
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 312
telemt_me_keepalive_timeout_total 1754
telemt_me_reconnect_attempts_total 42146
telemt_me_reconnect_success_total 18389
telemt_me_reader_eof_total 19948
telemt_me_idle_close_by_peer_total 19948
telemt_me_route_drop_no_conn_total 557742
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1335718
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3466
telemt_desync_full_logged_total 1027
telemt_desync_suppressed_total 2439
telemt_desync_frames_bucket_total{bucket="1_2"} 864
telemt_desync_frames_bucket_total{bucket="3_10"} 1307
telemt_desync_frames_bucket_total{bucket="gt_10"} 1295
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 19383
telemt_me_refill_failed_total 737
telemt_me_writer_restored_same_endpoint_total 18377
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 994
telemt_user_connections_total{user="hello"} 1335423
telemt_user_connections_current{user="hello"} 916
telemt_user_octets_from_client{user="hello"} 16345948269 (15.22 GB)
telemt_user_octets_to_client{user="hello"} 405408082009 (377.57 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 241
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 95275.2 (26h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1099360
telemt_connections_bad_total 77987
telemt_handshake_timeouts_total 105257
telemt_upstream_connect_attempt_total 25668
telemt_upstream_connect_success_total 25668
telemt_upstream_connect_attempts_per_request{bucket="1"} 25668
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14025
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11638
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1165
telemt_me_reconnect_attempts_total 23058
telemt_me_reconnect_success_total 20923
telemt_me_reader_eof_total 22183
telemt_me_idle_close_by_peer_total 22182
telemt_me_seq_mismatch_total 20
telemt_me_route_drop_no_conn_total 361340
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 882930
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 31
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1828
telemt_desync_full_logged_total 706
telemt_desync_suppressed_total 1122
telemt_desync_frames_bucket_total{bucket="1_2"} 656
telemt_desync_frames_bucket_total{bucket="3_10"} 639
telemt_desync_frames_bucket_total{bucket="gt_10"} 533
telemt_pool_swap_total 80
telemt_me_writer_removed_unexpected_total 21212
telemt_me_refill_failed_total 64
telemt_me_writer_restored_same_endpoint_total 20892
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 289
telemt_user_connections_total{user="hello"} 882235
telemt_user_connections_current{user="hello"} 546
telemt_user_octets_from_client{user="hello"} 10610893576 (9.88 GB)
telemt_user_octets_to_client{user="hello"} 261194880764 (243.26 GB)
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 95274.9 (26h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1212025
telemt_connections_bad_total 6958
telemt_handshake_timeouts_total 11950
telemt_upstream_connect_attempt_total 26077
telemt_upstream_connect_success_total 25962
telemt_upstream_connect_fail_total 115
telemt_upstream_connect_attempts_per_request{bucket="1"} 26077
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13264
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12489
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 204
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 115
telemt_me_keepalive_timeout_total 2153
telemt_me_reconnect_attempts_total 25168
telemt_me_reconnect_success_total 21069
telemt_me_reader_eof_total 22185
telemt_me_idle_close_by_peer_total 22185
telemt_me_route_drop_no_conn_total 432080
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1104846
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4318
telemt_desync_full_logged_total 1546
telemt_desync_suppressed_total 2772
telemt_desync_frames_bucket_total{bucket="1_2"} 1418
telemt_desync_frames_bucket_total{bucket="3_10"} 1615
telemt_desync_frames_bucket_total{bucket="gt_10"} 1285
telemt_pool_swap_total 61
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 21471
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 21069
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 402
telemt_user_connections_total{user="hello"} 1104544
telemt_user_connections_current{user="hello"} 521
telemt_user_octets_from_client{user="hello"} 20574557703 (19.16 GB)
telemt_user_octets_to_client{user="hello"} 383745849378 (357.39 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 174
telemt_user_unique_ips_recent_window{user="hello"} 83
```