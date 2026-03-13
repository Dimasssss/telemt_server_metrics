# Server Metrics 2026-03-13 01:18:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 69561.9 (19h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2027205
telemt_connections_bad_total 26124
telemt_handshake_timeouts_total 21634
telemt_upstream_connect_attempt_total 13824
telemt_upstream_connect_success_total 13745
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 13824
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7095
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6609
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_keepalive_timeout_total 1250
telemt_me_reconnect_attempts_total 19110
telemt_me_reconnect_success_total 10250
telemt_me_reader_eof_total 11086
telemt_me_idle_close_by_peer_total 11085
telemt_me_route_drop_no_conn_total 790697
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1886178
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
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 10671
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 10237
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 421
telemt_user_connections_total{user="hello"} 1885636
telemt_user_connections_current{user="hello"} 604
telemt_user_octets_from_client{user="hello"} 27649045664 (25.75 GB)
telemt_user_octets_to_client{user="hello"} 659548578044 (614.25 GB)
telemt_user_unique_ips_current{user="hello"} 219
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 99182.5 (27h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 835250
telemt_connections_bad_total 11772
telemt_handshake_timeouts_total 31971
telemt_upstream_connect_attempt_total 25286
telemt_upstream_connect_success_total 25257
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 25286
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13155
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12013
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3444
telemt_me_reconnect_attempts_total 18754
telemt_me_reconnect_success_total 18650
telemt_me_reader_eof_total 19864
telemt_me_idle_close_by_peer_total 19864
telemt_me_route_drop_no_conn_total 269563
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 756631
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3066
telemt_desync_full_logged_total 962
telemt_desync_suppressed_total 2104
telemt_desync_frames_bucket_total{bucket="1_2"} 1242
telemt_desync_frames_bucket_total{bucket="3_10"} 996
telemt_desync_frames_bucket_total{bucket="gt_10"} 828
telemt_pool_swap_total 101
telemt_me_writer_removed_unexpected_total 18832
telemt_me_writer_restored_same_endpoint_total 18641
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 182
telemt_user_connections_total{user="hello"} 758535
telemt_user_connections_current{user="hello"} 246
telemt_user_octets_from_client{user="hello"} 12247323264 (11.41 GB)
telemt_user_octets_to_client{user="hello"} 286154284683 (266.50 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 99182.3 (27h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1736018
telemt_connections_bad_total 8965
telemt_handshake_timeouts_total 114921
telemt_upstream_connect_attempt_total 23188
telemt_upstream_connect_success_total 23178
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 23188
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12255
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10832
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1586
telemt_me_reconnect_attempts_total 19122
telemt_me_reconnect_success_total 17860
telemt_me_reader_eof_total 18914
telemt_me_idle_close_by_peer_total 18913
telemt_me_route_drop_no_conn_total 569227
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1363322
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
telemt_pool_swap_total 92
telemt_me_writer_removed_unexpected_total 18030
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 17819
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 170
telemt_user_connections_total{user="hello"} 1362919
telemt_user_connections_current{user="hello"} 372
telemt_user_octets_from_client{user="hello"} 20055792164 (18.68 GB)
telemt_user_octets_to_client{user="hello"} 495784267657 (461.74 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 140
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 99182.4 (27h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1088478
telemt_connections_bad_total 13094
telemt_handshake_timeouts_total 72425
telemt_upstream_connect_attempt_total 34540
telemt_upstream_connect_success_total 32273
telemt_upstream_connect_fail_total 2130
telemt_upstream_connect_attempts_per_request{bucket="1"} 34266
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19981
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12203
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2129
telemt_me_keepalive_timeout_total 11271
telemt_me_reconnect_attempts_total 29293
telemt_me_reconnect_success_total 21452
telemt_me_reader_eof_total 23217
telemt_me_idle_close_by_peer_total 23210
telemt_me_route_drop_no_conn_total 384701
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 932733
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
telemt_me_writer_removed_unexpected_total 21831
telemt_me_refill_failed_total 241
telemt_me_writer_restored_same_endpoint_total 21430
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 2298
telemt_me_writer_removed_unexpected_minus_restored_total 379
telemt_user_connections_total{user="hello"} 937921
telemt_user_connections_current{user="hello"} 226
telemt_user_octets_from_client{user="hello"} 14446303393 (13.45 GB)
telemt_user_octets_to_client{user="hello"} 368956799722 (343.62 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 99182.4 (27h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1198472
telemt_connections_bad_total 12582
telemt_handshake_timeouts_total 9371
telemt_upstream_connect_attempt_total 30153
telemt_upstream_connect_success_total 29772
telemt_upstream_connect_fail_total 381
telemt_upstream_connect_attempts_per_request{bucket="1"} 30153
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15158
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14449
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 154
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 381
telemt_me_keepalive_timeout_total 1844
telemt_me_reconnect_attempts_total 35853
telemt_me_reconnect_success_total 24807
telemt_me_reader_eof_total 26098
telemt_me_idle_close_by_peer_total 26098
telemt_me_seq_mismatch_total 35
telemt_me_route_drop_no_conn_total 449477
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1107020
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 39
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4146
telemt_desync_full_logged_total 1469
telemt_desync_suppressed_total 2677
telemt_desync_frames_bucket_total{bucket="1_2"} 1237
telemt_desync_frames_bucket_total{bucket="3_10"} 1376
telemt_desync_frames_bucket_total{bucket="gt_10"} 1533
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 25443
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 24761
telemt_me_writer_restored_fallback_total 46
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 636
telemt_user_connections_total{user="hello"} 1106876
telemt_user_connections_current{user="hello"} 272
telemt_user_octets_from_client{user="hello"} 13703670840 (12.76 GB)
telemt_user_octets_to_client{user="hello"} 382070375884 (355.83 GB)
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 48
```