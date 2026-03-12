# Server Metrics 2026-03-12 13:18:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 26380.4 (7h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 913378
telemt_connections_bad_total 5297
telemt_handshake_timeouts_total 8250
telemt_upstream_connect_attempt_total 5200
telemt_upstream_connect_success_total 5168
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 5200
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2795
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2366
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 7700
telemt_me_reconnect_success_total 3802
telemt_me_reader_eof_total 4081
telemt_me_idle_close_by_peer_total 4080
telemt_me_route_drop_no_conn_total 323918
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 873702
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4666
telemt_desync_full_logged_total 1178
telemt_desync_suppressed_total 3488
telemt_desync_frames_bucket_total{bucket="1_2"} 1165
telemt_desync_frames_bucket_total{bucket="3_10"} 1697
telemt_desync_frames_bucket_total{bucket="gt_10"} 1804
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 3965
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 3789
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 163
telemt_user_connections_total{user="hello"} 873522
telemt_user_connections_current{user="hello"} 1577
telemt_user_octets_from_client{user="hello"} 14508796804 (13.51 GB)
telemt_user_octets_to_client{user="hello"} 260535737572 (242.64 GB)
telemt_user_unique_ips_current{user="hello"} 423
telemt_user_unique_ips_recent_window{user="hello"} 218
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 56000.8 (15h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 449666
telemt_connections_bad_total 5283
telemt_handshake_timeouts_total 24534
telemt_upstream_connect_attempt_total 13574
telemt_upstream_connect_success_total 13567
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 13574
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6673
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6878
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1070
telemt_me_reconnect_attempts_total 10632
telemt_me_reconnect_success_total 10574
telemt_me_reader_eof_total 11245
telemt_me_idle_close_by_peer_total 11245
telemt_me_route_drop_no_conn_total 129196
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 397015
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1342
telemt_desync_full_logged_total 438
telemt_desync_suppressed_total 904
telemt_desync_frames_bucket_total{bucket="1_2"} 546
telemt_desync_frames_bucket_total{bucket="3_10"} 459
telemt_desync_frames_bucket_total{bucket="gt_10"} 337
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 10670
telemt_me_writer_restored_same_endpoint_total 10565
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 96
telemt_user_connections_total{user="hello"} 397483
telemt_user_connections_current{user="hello"} 618
telemt_user_octets_from_client{user="hello"} 5956545747 (5.55 GB)
telemt_user_octets_to_client{user="hello"} 143766846190 (133.89 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 166
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 56000.8 (15h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 991861
telemt_connections_bad_total 5443
telemt_handshake_timeouts_total 74921
telemt_upstream_connect_attempt_total 13525
telemt_upstream_connect_success_total 13520
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 13525
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7368
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6095
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 866
telemt_me_reconnect_attempts_total 10442
telemt_me_reconnect_success_total 10349
telemt_me_reader_eof_total 10905
telemt_me_idle_close_by_peer_total 10905
telemt_me_route_drop_no_conn_total 250377
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 693460
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3039
telemt_desync_full_logged_total 918
telemt_desync_suppressed_total 2121
telemt_desync_frames_bucket_total{bucket="1_2"} 433
telemt_desync_frames_bucket_total{bucket="3_10"} 1091
telemt_desync_frames_bucket_total{bucket="gt_10"} 1515
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 10382
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 10308
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 693680
telemt_user_connections_current{user="hello"} 973
telemt_user_octets_from_client{user="hello"} 9190715284 (8.56 GB)
telemt_user_octets_to_client{user="hello"} 223679209229 (208.32 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 263
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 56001.2 (15h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 562621
telemt_connections_bad_total 7646
telemt_handshake_timeouts_total 52656
telemt_upstream_connect_attempt_total 14969
telemt_upstream_connect_success_total 14908
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 14969
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8472
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6424
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_keepalive_timeout_total 1273
telemt_me_reconnect_attempts_total 13326
telemt_me_reconnect_success_total 12094
telemt_me_reader_eof_total 12835
telemt_me_idle_close_by_peer_total 12835
telemt_me_route_drop_no_conn_total 188880
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 471621
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 956
telemt_desync_full_logged_total 334
telemt_desync_suppressed_total 622
telemt_desync_frames_bucket_total{bucket="1_2"} 276
telemt_desync_frames_bucket_total{bucket="3_10"} 392
telemt_desync_frames_bucket_total{bucket="gt_10"} 288
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 12224
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 12073
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 130
telemt_user_connections_total{user="hello"} 471130
telemt_user_connections_current{user="hello"} 659
telemt_user_octets_from_client{user="hello"} 5331094784 (4.96 GB)
telemt_user_octets_to_client{user="hello"} 190121341844 (177.06 GB)
telemt_user_unique_ips_current{user="hello"} 184
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 56001.0 (15h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 634490
telemt_connections_bad_total 1736
telemt_handshake_timeouts_total 5173
telemt_upstream_connect_attempt_total 17905
telemt_upstream_connect_success_total 17687
telemt_upstream_connect_fail_total 218
telemt_upstream_connect_attempts_per_request{bucket="1"} 17905
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8992
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8596
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 92
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 218
telemt_me_keepalive_timeout_total 974
telemt_me_reconnect_attempts_total 22093
telemt_me_reconnect_success_total 14866
telemt_me_reader_eof_total 15594
telemt_me_idle_close_by_peer_total 15594
telemt_me_seq_mismatch_total 22
telemt_me_route_drop_no_conn_total 216025
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 591123
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 26
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2479
telemt_desync_full_logged_total 835
telemt_desync_suppressed_total 1644
telemt_desync_frames_bucket_total{bucket="1_2"} 684
telemt_desync_frames_bucket_total{bucket="3_10"} 881
telemt_desync_frames_bucket_total{bucket="gt_10"} 914
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 15237
telemt_me_refill_failed_total 224
telemt_me_writer_restored_same_endpoint_total 14839
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 371
telemt_user_connections_total{user="hello"} 591034
telemt_user_connections_current{user="hello"} 842
telemt_user_octets_from_client{user="hello"} 6808148756 (6.34 GB)
telemt_user_octets_to_client{user="hello"} 157030687924 (146.25 GB)
telemt_user_unique_ips_current{user="hello"} 229
telemt_user_unique_ips_recent_window{user="hello"} 109
```