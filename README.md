# Server Metrics 2026-03-11 15:47:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 91236.2 (25h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2254574
telemt_connections_bad_total 39305
telemt_handshake_timeouts_total 53283
telemt_upstream_connect_attempt_total 19104
telemt_upstream_connect_success_total 19092
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 19104
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9609
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9390
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 92
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 4895
telemt_me_reconnect_attempts_total 32333
telemt_me_reconnect_success_total 14465
telemt_me_reader_eof_total 15701
telemt_me_idle_close_by_peer_total 15701
telemt_me_route_drop_no_conn_total 834827
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2061398
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10720
telemt_desync_full_logged_total 2913
telemt_desync_suppressed_total 7807
telemt_desync_frames_bucket_total{bucket="1_2"} 2660
telemt_desync_frames_bucket_total{bucket="3_10"} 4129
telemt_desync_frames_bucket_total{bucket="gt_10"} 3931
telemt_pool_swap_total 67
telemt_me_writer_removed_unexpected_total 15183
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 14459
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 718
telemt_user_connections_total{user="hello"} 2059846
telemt_user_connections_current{user="hello"} 1355
telemt_user_octets_from_client{user="hello"} 27576987448 (25.68 GB)
telemt_user_octets_to_client{user="hello"} 583992181664 (543.89 GB)
telemt_user_unique_ips_current{user="hello"} 381
telemt_user_unique_ips_recent_window{user="hello"} 201
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 91292.9 (25h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 834700
telemt_connections_bad_total 13863
telemt_handshake_timeouts_total 56688
telemt_upstream_connect_attempt_total 29021
telemt_upstream_connect_success_total 26063
telemt_upstream_connect_fail_total 2958
telemt_upstream_connect_attempts_per_request{bucket="1"} 29021
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12140
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11675
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2039
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2958
telemt_me_keepalive_timeout_total 2559
telemt_me_reconnect_attempts_total 20615
telemt_me_reconnect_success_total 18522
telemt_me_reader_eof_total 19613
telemt_me_idle_close_by_peer_total 19610
telemt_me_route_drop_no_conn_total 327275
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 709712
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2905
telemt_desync_full_logged_total 926
telemt_desync_suppressed_total 1979
telemt_desync_frames_bucket_total{bucket="1_2"} 901
telemt_desync_frames_bucket_total{bucket="3_10"} 1042
telemt_desync_frames_bucket_total{bucket="gt_10"} 962
telemt_pool_swap_total 74
telemt_me_writer_removed_unexpected_total 18789
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 18499
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 267
telemt_user_connections_total{user="hello"} 712190
telemt_user_connections_current{user="hello"} 492
telemt_user_octets_from_client{user="hello"} 8247781958 (7.68 GB)
telemt_user_octets_to_client{user="hello"} 201980847444 (188.11 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 152
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 91292.8 (25h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1447291
telemt_connections_bad_total 8676
telemt_handshake_timeouts_total 124413
telemt_upstream_connect_attempt_total 23938
telemt_upstream_connect_success_total 23645
telemt_upstream_connect_fail_total 293
telemt_upstream_connect_attempts_per_request{bucket="1"} 23938
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12770
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10751
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 124
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 293
telemt_me_keepalive_timeout_total 1589
telemt_me_reconnect_attempts_total 39002
telemt_me_reconnect_success_total 17958
telemt_me_reader_eof_total 19421
telemt_me_idle_close_by_peer_total 19421
telemt_me_route_drop_no_conn_total 527768
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1261626
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3333
telemt_desync_full_logged_total 986
telemt_desync_suppressed_total 2347
telemt_desync_frames_bucket_total{bucket="1_2"} 820
telemt_desync_frames_bucket_total{bucket="3_10"} 1263
telemt_desync_frames_bucket_total{bucket="gt_10"} 1250
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 18860
telemt_me_refill_failed_total 653
telemt_me_writer_restored_same_endpoint_total 17947
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 902
telemt_user_connections_total{user="hello"} 1261342
telemt_user_connections_current{user="hello"} 878
telemt_user_octets_from_client{user="hello"} 15173839241 (14.13 GB)
telemt_user_octets_to_client{user="hello"} 380323192361 (354.20 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 251
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 91293.4 (25h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1039582
telemt_connections_bad_total 77959
telemt_handshake_timeouts_total 101777
telemt_upstream_connect_attempt_total 24496
telemt_upstream_connect_success_total 24496
telemt_upstream_connect_attempts_per_request{bucket="1"} 24496
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13411
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11080
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1014
telemt_me_reconnect_attempts_total 21008
telemt_me_reconnect_success_total 19933
telemt_me_reader_eof_total 21122
telemt_me_idle_close_by_peer_total 21121
telemt_me_seq_mismatch_total 19
telemt_me_route_drop_no_conn_total 340400
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 831479
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 30
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1744
telemt_desync_full_logged_total 670
telemt_desync_suppressed_total 1074
telemt_desync_frames_bucket_total{bucket="1_2"} 627
telemt_desync_frames_bucket_total{bucket="3_10"} 612
telemt_desync_frames_bucket_total{bucket="gt_10"} 505
telemt_pool_swap_total 79
telemt_me_writer_removed_unexpected_total 20174
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 19903
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 241
telemt_user_connections_total{user="hello"} 830799
telemt_user_connections_current{user="hello"} 599
telemt_user_octets_from_client{user="hello"} 9946780032 (9.26 GB)
telemt_user_octets_to_client{user="hello"} 245359514492 (228.51 GB)
telemt_user_unique_ips_current{user="hello"} 160
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 91293.1 (25h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1150124
telemt_connections_bad_total 6940
telemt_handshake_timeouts_total 11535
telemt_upstream_connect_attempt_total 24772
telemt_upstream_connect_success_total 24661
telemt_upstream_connect_fail_total 111
telemt_upstream_connect_attempts_per_request{bucket="1"} 24772
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12595
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11862
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 199
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 111
telemt_me_keepalive_timeout_total 1953
telemt_me_reconnect_attempts_total 24044
telemt_me_reconnect_success_total 19953
telemt_me_reader_eof_total 21029
telemt_me_idle_close_by_peer_total 21029
telemt_me_route_drop_no_conn_total 409939
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1046509
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4025
telemt_desync_full_logged_total 1460
telemt_desync_suppressed_total 2565
telemt_desync_frames_bucket_total{bucket="1_2"} 1356
telemt_desync_frames_bucket_total{bucket="3_10"} 1505
telemt_desync_frames_bucket_total{bucket="gt_10"} 1164
telemt_pool_swap_total 60
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 20339
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 19953
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 386
telemt_user_connections_total{user="hello"} 1046213
telemt_user_connections_current{user="hello"} 779
telemt_user_octets_from_client{user="hello"} 15969577311 (14.87 GB)
telemt_user_octets_to_client{user="hello"} 365455963718 (340.36 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 204
telemt_user_unique_ips_recent_window{user="hello"} 101
```