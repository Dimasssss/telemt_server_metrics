# Server Metrics 2026-03-13 01:33:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 70479.3 (19h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2036789
telemt_connections_bad_total 26136
telemt_handshake_timeouts_total 21739
telemt_upstream_connect_attempt_total 13989
telemt_upstream_connect_success_total 13909
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 13989
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7176
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6692
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_keepalive_timeout_total 1252
telemt_me_reconnect_attempts_total 19231
telemt_me_reconnect_success_total 10371
telemt_me_reader_eof_total 11213
telemt_me_idle_close_by_peer_total 11212
telemt_me_route_drop_no_conn_total 793988
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1895292
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8683
telemt_desync_full_logged_total 2260
telemt_desync_suppressed_total 6423
telemt_desync_frames_bucket_total{bucket="1_2"} 2289
telemt_desync_frames_bucket_total{bucket="3_10"} 3130
telemt_desync_frames_bucket_total{bucket="gt_10"} 3264
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 10794
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 10358
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 423
telemt_user_connections_total{user="hello"} 1894749
telemt_user_connections_current{user="hello"} 537
telemt_user_octets_from_client{user="hello"} 27711239424 (25.81 GB)
telemt_user_octets_to_client{user="hello"} 661334536936 (615.92 GB)
telemt_user_unique_ips_current{user="hello"} 194
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 100099.8 (27h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 839628
telemt_connections_bad_total 11786
telemt_handshake_timeouts_total 31977
telemt_upstream_connect_attempt_total 25474
telemt_upstream_connect_success_total 25445
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 25474
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13245
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12111
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3447
telemt_me_reconnect_attempts_total 18899
telemt_me_reconnect_success_total 18794
telemt_me_reader_eof_total 20019
telemt_me_idle_close_by_peer_total 20019
telemt_me_route_drop_no_conn_total 270694
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 760926
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3072
telemt_desync_full_logged_total 965
telemt_desync_suppressed_total 2107
telemt_desync_frames_bucket_total{bucket="1_2"} 1246
telemt_desync_frames_bucket_total{bucket="3_10"} 998
telemt_desync_frames_bucket_total{bucket="gt_10"} 828
telemt_pool_swap_total 102
telemt_me_writer_removed_unexpected_total 18978
telemt_me_writer_restored_same_endpoint_total 18785
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 184
telemt_user_connections_total{user="hello"} 762830
telemt_user_connections_current{user="hello"} 213
telemt_user_octets_from_client{user="hello"} 12263488128 (11.42 GB)
telemt_user_octets_to_client{user="hello"} 286880409835 (267.18 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 100099.7 (27h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1743547
telemt_connections_bad_total 8974
telemt_handshake_timeouts_total 116170
telemt_upstream_connect_attempt_total 23391
telemt_upstream_connect_success_total 23381
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 23391
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12354
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10934
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 88
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1590
telemt_me_reconnect_attempts_total 19282
telemt_me_reconnect_success_total 18019
telemt_me_reader_eof_total 19084
telemt_me_idle_close_by_peer_total 19083
telemt_me_route_drop_no_conn_total 571375
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1369515
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4997
telemt_desync_full_logged_total 1533
telemt_desync_suppressed_total 3464
telemt_desync_frames_bucket_total{bucket="1_2"} 798
telemt_desync_frames_bucket_total{bucket="3_10"} 1807
telemt_desync_frames_bucket_total{bucket="gt_10"} 2392
telemt_pool_swap_total 93
telemt_me_writer_removed_unexpected_total 18190
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 17978
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 171
telemt_user_connections_total{user="hello"} 1369112
telemt_user_connections_current{user="hello"} 276
telemt_user_octets_from_client{user="hello"} 20091299344 (18.71 GB)
telemt_user_octets_to_client{user="hello"} 497711511917 (463.53 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 100099.7 (27h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1092510
telemt_connections_bad_total 13096
telemt_handshake_timeouts_total 72497
telemt_upstream_connect_attempt_total 34833
telemt_upstream_connect_success_total 32563
telemt_upstream_connect_fail_total 2133
telemt_upstream_connect_attempts_per_request{bucket="1"} 34559
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20153
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12321
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2132
telemt_me_keepalive_timeout_total 11274
telemt_me_reconnect_attempts_total 29537
telemt_me_reconnect_success_total 21695
telemt_me_reader_eof_total 23467
telemt_me_idle_close_by_peer_total 23460
telemt_me_route_drop_no_conn_total 386016
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 936523
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1895
telemt_desync_full_logged_total 628
telemt_desync_suppressed_total 1267
telemt_desync_frames_bucket_total{bucket="1_2"} 522
telemt_desync_frames_bucket_total{bucket="3_10"} 743
telemt_desync_frames_bucket_total{bucket="gt_10"} 630
telemt_pool_swap_total 86
telemt_me_writer_removed_unexpected_total 22077
telemt_me_refill_failed_total 241
telemt_me_writer_restored_same_endpoint_total 21673
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 2298
telemt_me_writer_removed_unexpected_minus_restored_total 382
telemt_user_connections_total{user="hello"} 941711
telemt_user_connections_current{user="hello"} 188
telemt_user_octets_from_client{user="hello"} 14468894289 (13.48 GB)
telemt_user_octets_to_client{user="hello"} 369731210626 (344.34 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 100100.0 (27h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1204483
telemt_connections_bad_total 12584
telemt_handshake_timeouts_total 9409
telemt_upstream_connect_attempt_total 30634
telemt_upstream_connect_success_total 30250
telemt_upstream_connect_fail_total 384
telemt_upstream_connect_attempts_per_request{bucket="1"} 30634
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15432
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14650
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 156
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 384
telemt_me_keepalive_timeout_total 1854
telemt_me_reconnect_attempts_total 36288
telemt_me_reconnect_success_total 25241
telemt_me_reader_eof_total 26534
telemt_me_idle_close_by_peer_total 26534
telemt_me_seq_mismatch_total 36
telemt_me_route_drop_no_conn_total 451452
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1112805
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 40
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4160
telemt_desync_full_logged_total 1474
telemt_desync_suppressed_total 2686
telemt_desync_frames_bucket_total{bucket="1_2"} 1245
telemt_desync_frames_bucket_total{bucket="3_10"} 1379
telemt_desync_frames_bucket_total{bucket="gt_10"} 1536
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 25880
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 25194
telemt_me_writer_restored_fallback_total 47
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 639
telemt_user_connections_total{user="hello"} 1112661
telemt_user_connections_current{user="hello"} 261
telemt_user_octets_from_client{user="hello"} 13726816356 (12.78 GB)
telemt_user_octets_to_client{user="hello"} 382686908472 (356.40 GB)
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 34
```