# Server Metrics 2026-03-12 11:15:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 19033.5 (5h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 642037
telemt_connections_bad_total 1492
telemt_handshake_timeouts_total 3751
telemt_upstream_connect_attempt_total 3636
telemt_upstream_connect_success_total 3610
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 3636
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2007
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1600
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 312
telemt_me_reconnect_attempts_total 6496
telemt_me_reconnect_success_total 2606
telemt_me_reader_eof_total 2818
telemt_me_idle_close_by_peer_total 2818
telemt_me_route_drop_no_conn_total 222696
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 618401
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3075
telemt_desync_full_logged_total 774
telemt_desync_suppressed_total 2301
telemt_desync_frames_bucket_total{bucket="1_2"} 775
telemt_desync_frames_bucket_total{bucket="3_10"} 1132
telemt_desync_frames_bucket_total{bucket="gt_10"} 1168
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 2753
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 2593
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 147
telemt_user_connections_total{user="hello"} 618260
telemt_user_connections_current{user="hello"} 1517
telemt_user_octets_from_client{user="hello"} 10922079220 (10.17 GB)
telemt_user_octets_to_client{user="hello"} 170565677420 (158.85 GB)
telemt_user_unique_ips_current{user="hello"} 411
telemt_user_unique_ips_recent_window{user="hello"} 272
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 48654.0 (13h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 340610
telemt_connections_bad_total 3712
telemt_handshake_timeouts_total 11784
telemt_upstream_connect_attempt_total 12047
telemt_upstream_connect_success_total 12041
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 12047
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5913
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6113
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 683
telemt_me_reconnect_attempts_total 9481
telemt_me_reconnect_success_total 9428
telemt_me_reader_eof_total 10019
telemt_me_idle_close_by_peer_total 10019
telemt_me_route_drop_no_conn_total 98084
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 304818
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 767
telemt_desync_full_logged_total 271
telemt_desync_suppressed_total 496
telemt_desync_frames_bucket_total{bucket="1_2"} 260
telemt_desync_frames_bucket_total{bucket="3_10"} 274
telemt_desync_frames_bucket_total{bucket="gt_10"} 233
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 9510
telemt_me_writer_restored_same_endpoint_total 9419
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 305248
telemt_user_connections_current{user="hello"} 662
telemt_user_octets_from_client{user="hello"} 4134893035 (3.85 GB)
telemt_user_octets_to_client{user="hello"} 108787184954 (101.32 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 172
telemt_user_unique_ips_recent_window{user="hello"} 112
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 48653.8 (13h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 814646
telemt_connections_bad_total 4081
telemt_handshake_timeouts_total 59791
telemt_upstream_connect_attempt_total 12044
telemt_upstream_connect_success_total 12039
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 12044
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6644
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5341
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 595
telemt_me_reconnect_attempts_total 9336
telemt_me_reconnect_success_total 9258
telemt_me_reader_eof_total 9734
telemt_me_idle_close_by_peer_total 9734
telemt_me_route_drop_no_conn_total 189659
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 536219
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2425
telemt_desync_full_logged_total 720
telemt_desync_suppressed_total 1705
telemt_desync_frames_bucket_total{bucket="1_2"} 311
telemt_desync_frames_bucket_total{bucket="3_10"} 840
telemt_desync_frames_bucket_total{bucket="gt_10"} 1274
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 9276
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 9217
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 536467
telemt_user_connections_current{user="hello"} 856
telemt_user_octets_from_client{user="hello"} 7304306836 (6.80 GB)
telemt_user_octets_to_client{user="hello"} 171058122081 (159.31 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 253
telemt_user_unique_ips_recent_window{user="hello"} 154
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 48654.3 (13h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 432498
telemt_connections_bad_total 2491
telemt_handshake_timeouts_total 38179
telemt_upstream_connect_attempt_total 12928
telemt_upstream_connect_success_total 12877
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 12928
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7310
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5558
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_timeout_total 861
telemt_me_reconnect_attempts_total 10496
telemt_me_reconnect_success_total 10455
telemt_me_reader_eof_total 11091
telemt_me_idle_close_by_peer_total 11091
telemt_me_route_drop_no_conn_total 144098
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 362521
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 751
telemt_desync_full_logged_total 263
telemt_desync_suppressed_total 488
telemt_desync_frames_bucket_total{bucket="1_2"} 229
telemt_desync_frames_bucket_total{bucket="3_10"} 313
telemt_desync_frames_bucket_total{bucket="gt_10"} 209
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 10527
telemt_me_writer_restored_same_endpoint_total 10434
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 362346
telemt_user_connections_current{user="hello"} 681
telemt_user_octets_from_client{user="hello"} 4210399536 (3.92 GB)
telemt_user_octets_to_client{user="hello"} 137707628468 (128.25 GB)
telemt_user_unique_ips_current{user="hello"} 197
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 48654.2 (13h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 491567
telemt_connections_bad_total 1657
telemt_handshake_timeouts_total 3744
telemt_upstream_connect_attempt_total 15674
telemt_upstream_connect_success_total 15487
telemt_upstream_connect_fail_total 187
telemt_upstream_connect_attempts_per_request{bucket="1"} 15674
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8018
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7384
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 79
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 187
telemt_me_keepalive_timeout_total 653
telemt_me_reconnect_attempts_total 14583
telemt_me_reconnect_success_total 13057
telemt_me_reader_eof_total 13571
telemt_me_idle_close_by_peer_total 13571
telemt_me_seq_mismatch_total 21
telemt_me_route_drop_no_conn_total 160071
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 460923
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1908
telemt_desync_full_logged_total 637
telemt_desync_suppressed_total 1271
telemt_desync_frames_bucket_total{bucket="1_2"} 565
telemt_desync_frames_bucket_total{bucket="3_10"} 659
telemt_desync_frames_bucket_total{bucket="gt_10"} 684
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 13231
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 13031
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 174
telemt_user_connections_total{user="hello"} 460856
telemt_user_connections_current{user="hello"} 851
telemt_user_octets_from_client{user="hello"} 5257451060 (4.90 GB)
telemt_user_octets_to_client{user="hello"} 113604329548 (105.80 GB)
telemt_user_unique_ips_current{user="hello"} 226
telemt_user_unique_ips_recent_window{user="hello"} 155
```