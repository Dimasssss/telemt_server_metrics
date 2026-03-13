# Server Metrics 2026-03-13 21:43:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 143073.4 (39h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4492588
telemt_connections_bad_total 38133
telemt_handshake_timeouts_total 106670
telemt_upstream_connect_attempt_total 29868
telemt_upstream_connect_success_total 29662
telemt_upstream_connect_fail_total 206
telemt_upstream_connect_attempts_per_request{bucket="1"} 29868
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16294
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13224
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 144
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 206
telemt_me_keepalive_timeout_total 6621
telemt_me_reconnect_attempts_total 30330
telemt_me_reconnect_success_total 20210
telemt_me_reader_eof_total 21684
telemt_me_idle_close_by_peer_total 21683
telemt_me_route_drop_no_conn_total 1694939
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4116146
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16388
telemt_desync_full_logged_total 4387
telemt_desync_suppressed_total 12001
telemt_desync_frames_bucket_total{bucket="1_2"} 4086
telemt_desync_frames_bucket_total{bucket="3_10"} 6260
telemt_desync_frames_bucket_total{bucket="gt_10"} 6042
telemt_pool_swap_total 121
telemt_me_writer_removed_unexpected_total 20818
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 20197
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 608
telemt_user_connections_total{user="hello"} 4118275
telemt_user_connections_current{user="hello"} 887
telemt_user_octets_from_client{user="hello"} 60512067048 (56.36 GB)
telemt_user_octets_to_client{user="hello"} 1304616863157 (1.19 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 262
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 42737.1 (11h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 577579
telemt_connections_bad_total 41499
telemt_handshake_timeouts_total 12335
telemt_upstream_connect_attempt_total 12130
telemt_upstream_connect_success_total 11906
telemt_upstream_connect_fail_total 224
telemt_upstream_connect_attempts_per_request{bucket="1"} 12130
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6913
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4774
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 21
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 198
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 224
telemt_me_keepalive_timeout_total 1900
telemt_me_reconnect_attempts_total 11150
telemt_me_reconnect_success_total 7725
telemt_me_reader_eof_total 8174
telemt_me_idle_close_by_peer_total 8173
telemt_me_route_drop_no_conn_total 211939
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 501218
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1641
telemt_desync_full_logged_total 443
telemt_desync_suppressed_total 1198
telemt_desync_frames_bucket_total{bucket="1_2"} 348
telemt_desync_frames_bucket_total{bucket="3_10"} 711
telemt_desync_frames_bucket_total{bucket="gt_10"} 582
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 7939
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 7717
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 214
telemt_user_connections_total{user="hello"} 503149
telemt_user_connections_current{user="hello"} 270
telemt_user_octets_from_client{user="hello"} 5427320633 (5.05 GB)
telemt_user_octets_to_client{user="hello"} 165013084804 (153.68 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 99
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 172693.9 (47h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3268907
telemt_connections_bad_total 31391
telemt_handshake_timeouts_total 219395
telemt_upstream_connect_attempt_total 38302
telemt_upstream_connect_success_total 38281
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 38302
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19965
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18096
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 213
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10260
telemt_me_reconnect_attempts_total 34322
telemt_me_reconnect_success_total 29373
telemt_me_reader_eof_total 31172
telemt_me_idle_close_by_peer_total 31171
telemt_me_route_drop_no_conn_total 1118890
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2711792
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8910
telemt_desync_full_logged_total 2991
telemt_desync_suppressed_total 5919
telemt_desync_frames_bucket_total{bucket="1_2"} 1469
telemt_desync_frames_bucket_total{bucket="3_10"} 3246
telemt_desync_frames_bucket_total{bucket="gt_10"} 4195
telemt_pool_swap_total 159
telemt_me_writer_removed_unexpected_total 29806
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 29332
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 433
telemt_user_connections_total{user="hello"} 2711063
telemt_user_connections_current{user="hello"} 529
telemt_user_octets_from_client{user="hello"} 44400318428 (41.35 GB)
telemt_user_octets_to_client{user="hello"} 956988384653 (891.26 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 172
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 172696.4 (47h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2127687
telemt_connections_bad_total 22811
telemt_handshake_timeouts_total 210550
telemt_upstream_connect_attempt_total 53627
telemt_upstream_connect_success_total 51183
telemt_upstream_connect_fail_total 2307
telemt_upstream_connect_attempts_per_request{bucket="1"} 53353
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30663
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20356
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 164
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2306
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20238
telemt_me_reconnect_attempts_total 44586
telemt_me_reconnect_success_total 35573
telemt_me_reader_eof_total 38174
telemt_me_idle_close_by_peer_total 38167
telemt_me_route_drop_no_conn_total 748819
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1745431
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3778
telemt_desync_full_logged_total 1206
telemt_desync_suppressed_total 2572
telemt_desync_frames_bucket_total{bucket="1_2"} 998
telemt_desync_frames_bucket_total{bucket="3_10"} 1574
telemt_desync_frames_bucket_total{bucket="gt_10"} 1206
telemt_pool_swap_total 151
telemt_me_writer_removed_unexpected_total 36162
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 35549
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 589
telemt_user_connections_total{user="hello"} 1751313
telemt_user_connections_current{user="hello"} 337
telemt_user_octets_from_client{user="hello"} 27059006003 (25.20 GB)
telemt_user_octets_to_client{user="hello"} 655308556018 (610.30 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 42130.0 (11h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 616783
telemt_connections_bad_total 5842
telemt_handshake_timeouts_total 5669
telemt_upstream_connect_attempt_total 9442
telemt_upstream_connect_success_total 9137
telemt_upstream_connect_fail_total 305
telemt_upstream_connect_attempts_per_request{bucket="1"} 9442
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4412
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4704
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 305
telemt_me_keepalive_timeout_total 978
telemt_me_reconnect_attempts_total 31650
telemt_me_reconnect_success_total 7029
telemt_me_reader_eof_total 7930
telemt_me_idle_close_by_peer_total 7929
telemt_me_route_drop_no_conn_total 234539
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 578129
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1523
telemt_desync_full_logged_total 476
telemt_desync_suppressed_total 1047
telemt_desync_frames_bucket_total{bucket="1_2"} 462
telemt_desync_frames_bucket_total{bucket="3_10"} 602
telemt_desync_frames_bucket_total{bucket="gt_10"} 459
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 7860
telemt_me_refill_failed_total 767
telemt_me_writer_restored_same_endpoint_total 7025
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 831
telemt_user_connections_total{user="hello"} 578041
telemt_user_connections_current{user="hello"} 376
telemt_user_octets_from_client{user="hello"} 8529883996 (7.94 GB)
telemt_user_octets_to_client{user="hello"} 183948188484 (171.32 GB)
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 38
```