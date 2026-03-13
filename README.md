# Server Metrics 2026-03-13 00:57:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 68338.3 (18h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2014282
telemt_connections_bad_total 26115
telemt_handshake_timeouts_total 21508
telemt_upstream_connect_attempt_total 13545
telemt_upstream_connect_success_total 13468
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 13545
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6950
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6478
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_keepalive_timeout_total 1247
telemt_me_reconnect_attempts_total 18919
telemt_me_reconnect_success_total 10060
telemt_me_reader_eof_total 10881
telemt_me_idle_close_by_peer_total 10880
telemt_me_route_drop_no_conn_total 786499
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1873996
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8668
telemt_desync_full_logged_total 2258
telemt_desync_suppressed_total 6410
telemt_desync_frames_bucket_total{bucket="1_2"} 2288
telemt_desync_frames_bucket_total{bucket="3_10"} 3124
telemt_desync_frames_bucket_total{bucket="gt_10"} 3256
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 10479
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 10047
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 419
telemt_user_connections_total{user="hello"} 1873454
telemt_user_connections_current{user="hello"} 581
telemt_user_octets_from_client{user="hello"} 27577533720 (25.68 GB)
telemt_user_octets_to_client{user="hello"} 657493927700 (612.34 GB)
telemt_user_unique_ips_current{user="hello"} 200
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 97958.8 (27h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 829638
telemt_connections_bad_total 11755
telemt_handshake_timeouts_total 31923
telemt_upstream_connect_attempt_total 24940
telemt_upstream_connect_success_total 24911
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 24940
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12987
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11835
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3441
telemt_me_reconnect_attempts_total 18494
telemt_me_reconnect_success_total 18392
telemt_me_reader_eof_total 19578
telemt_me_idle_close_by_peer_total 19578
telemt_me_route_drop_no_conn_total 268285
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 751409
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3056
telemt_desync_full_logged_total 958
telemt_desync_suppressed_total 2098
telemt_desync_frames_bucket_total{bucket="1_2"} 1236
telemt_desync_frames_bucket_total{bucket="3_10"} 992
telemt_desync_frames_bucket_total{bucket="gt_10"} 828
telemt_pool_swap_total 99
telemt_me_writer_removed_unexpected_total 18571
telemt_me_writer_restored_same_endpoint_total 18383
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 179
telemt_user_connections_total{user="hello"} 753312
telemt_user_connections_current{user="hello"} 209
telemt_user_octets_from_client{user="hello"} 12212601776 (11.37 GB)
telemt_user_octets_to_client{user="hello"} 285612062675 (266.00 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 97958.6 (27h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1726876
telemt_connections_bad_total 8792
telemt_handshake_timeouts_total 113825
telemt_upstream_connect_attempt_total 22749
telemt_upstream_connect_success_total 22739
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 22749
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12049
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10601
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1580
telemt_me_reconnect_attempts_total 18771
telemt_me_reconnect_success_total 17509
telemt_me_reader_eof_total 18545
telemt_me_idle_close_by_peer_total 18544
telemt_me_route_drop_no_conn_total 566781
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1355588
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4994
telemt_desync_full_logged_total 1532
telemt_desync_suppressed_total 3462
telemt_desync_frames_bucket_total{bucket="1_2"} 798
telemt_desync_frames_bucket_total{bucket="3_10"} 1806
telemt_desync_frames_bucket_total{bucket="gt_10"} 2390
telemt_pool_swap_total 91
telemt_me_writer_removed_unexpected_total 17678
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 17468
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 169
telemt_user_connections_total{user="hello"} 1355188
telemt_user_connections_current{user="hello"} 268
telemt_user_octets_from_client{user="hello"} 19995325436 (18.62 GB)
telemt_user_octets_to_client{user="hello"} 493664794469 (459.76 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 97958.7 (27h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1082807
telemt_connections_bad_total 13088
telemt_handshake_timeouts_total 72249
telemt_upstream_connect_attempt_total 34138
telemt_upstream_connect_success_total 31874
telemt_upstream_connect_fail_total 2127
telemt_upstream_connect_attempts_per_request{bucket="1"} 33864
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19731
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12055
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 88
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2126
telemt_me_keepalive_timeout_total 11268
telemt_me_reconnect_attempts_total 28980
telemt_me_reconnect_success_total 21139
telemt_me_reader_eof_total 22878
telemt_me_idle_close_by_peer_total 22871
telemt_me_route_drop_no_conn_total 382156
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 927491
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
telemt_pool_swap_total 84
telemt_me_writer_removed_unexpected_total 21516
telemt_me_refill_failed_total 241
telemt_me_writer_restored_same_endpoint_total 21117
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 2298
telemt_me_writer_removed_unexpected_minus_restored_total 377
telemt_user_connections_total{user="hello"} 932682
telemt_user_connections_current{user="hello"} 222
telemt_user_octets_from_client{user="hello"} 14425169157 (13.43 GB)
telemt_user_octets_to_client{user="hello"} 367785250954 (342.53 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 97958.8 (27h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1192036
telemt_connections_bad_total 12579
telemt_handshake_timeouts_total 9359
telemt_upstream_connect_attempt_total 29617
telemt_upstream_connect_success_total 29243
telemt_upstream_connect_fail_total 373
telemt_upstream_connect_attempts_per_request{bucket="1"} 29616
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14892
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14186
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 154
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 373
telemt_me_keepalive_timeout_total 1836
telemt_me_reconnect_attempts_total 35412
telemt_me_reconnect_success_total 24366
telemt_me_reader_eof_total 25649
telemt_me_idle_close_by_peer_total 25649
telemt_me_seq_mismatch_total 35
telemt_me_route_drop_no_conn_total 446839
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1100711
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 39
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4120
telemt_desync_full_logged_total 1454
telemt_desync_suppressed_total 2666
telemt_desync_frames_bucket_total{bucket="1_2"} 1217
telemt_desync_frames_bucket_total{bucket="3_10"} 1374
telemt_desync_frames_bucket_total{bucket="gt_10"} 1529
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 24994
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 24320
telemt_me_writer_restored_fallback_total 46
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 628
telemt_user_connections_total{user="hello"} 1100567
telemt_user_connections_current{user="hello"} 240
telemt_user_octets_from_client{user="hello"} 13679387336 (12.74 GB)
telemt_user_octets_to_client{user="hello"} 381613952424 (355.41 GB)
telemt_user_unique_ips_current{user="hello"} 98
telemt_user_unique_ips_recent_window{user="hello"} 42
```