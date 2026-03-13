# Server Metrics 2026-03-13 18:29:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 131454.1 (36h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4201088
telemt_connections_bad_total 37621
telemt_handshake_timeouts_total 102354
telemt_upstream_connect_attempt_total 27738
telemt_upstream_connect_success_total 27558
telemt_upstream_connect_fail_total 180
telemt_upstream_connect_attempts_per_request{bucket="1"} 27738
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15243
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12192
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 123
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 180
telemt_me_keepalive_timeout_total 5784
telemt_me_reconnect_attempts_total 28768
telemt_me_reconnect_success_total 18661
telemt_me_reader_eof_total 20035
telemt_me_idle_close_by_peer_total 20034
telemt_me_route_drop_no_conn_total 1571879
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3839532
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 15013
telemt_desync_full_logged_total 3994
telemt_desync_suppressed_total 11019
telemt_desync_frames_bucket_total{bucket="1_2"} 3725
telemt_desync_frames_bucket_total{bucket="3_10"} 5717
telemt_desync_frames_bucket_total{bucket="gt_10"} 5571
telemt_pool_swap_total 110
telemt_me_writer_removed_unexpected_total 19241
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 18648
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 580
telemt_user_connections_total{user="hello"} 3841706
telemt_user_connections_current{user="hello"} 1430
telemt_user_octets_from_client{user="hello"} 53799346380 (50.10 GB)
telemt_user_octets_to_client{user="hello"} 1201001323525 (1.09 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 418
telemt_user_unique_ips_recent_window{user="hello"} 190
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 31118.0 (8h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 460571
telemt_connections_bad_total 35825
telemt_handshake_timeouts_total 10754
telemt_upstream_connect_attempt_total 8823
telemt_upstream_connect_success_total 8641
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 8823
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4936
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3541
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_keepalive_timeout_total 1613
telemt_me_reconnect_attempts_total 9037
telemt_me_reconnect_success_total 5637
telemt_me_reader_eof_total 5952
telemt_me_idle_close_by_peer_total 5951
telemt_me_route_drop_no_conn_total 173455
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 400792
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1399
telemt_desync_full_logged_total 367
telemt_desync_suppressed_total 1032
telemt_desync_frames_bucket_total{bucket="1_2"} 276
telemt_desync_frames_bucket_total{bucket="3_10"} 643
telemt_desync_frames_bucket_total{bucket="gt_10"} 480
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 5819
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 5629
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 182
telemt_user_connections_total{user="hello"} 402129
telemt_user_connections_current{user="hello"} 381
telemt_user_octets_from_client{user="hello"} 4150498559 (3.87 GB)
telemt_user_octets_to_client{user="hello"} 124321854036 (115.78 GB)
telemt_user_msgs_from_client{user="hello"} 4402
telemt_user_msgs_to_client{user="hello"} 9145
telemt_user_unique_ips_current{user="hello"} 142
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 161074.6 (44h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3070575
telemt_connections_bad_total 28916
telemt_handshake_timeouts_total 205613
telemt_upstream_connect_attempt_total 35812
telemt_upstream_connect_success_total 35802
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 35812
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18508
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17159
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 130
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3514
telemt_me_reconnect_attempts_total 30029
telemt_me_reconnect_success_total 27474
telemt_me_reader_eof_total 29131
telemt_me_idle_close_by_peer_total 29130
telemt_me_route_drop_no_conn_total 1050309
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2540291
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8557
telemt_desync_full_logged_total 2838
telemt_desync_suppressed_total 5719
telemt_desync_frames_bucket_total{bucket="1_2"} 1386
telemt_desync_frames_bucket_total{bucket="3_10"} 3128
telemt_desync_frames_bucket_total{bucket="gt_10"} 4043
telemt_pool_swap_total 151
telemt_me_writer_removed_unexpected_total 27795
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 27433
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 321
telemt_user_connections_total{user="hello"} 2539617
telemt_user_connections_current{user="hello"} 973
telemt_user_octets_from_client{user="hello"} 41967677088 (39.09 GB)
telemt_user_octets_to_client{user="hello"} 892053283793 (830.79 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 274
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 161075.2 (44h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1975449
telemt_connections_bad_total 20035
telemt_handshake_timeouts_total 181428
telemt_upstream_connect_attempt_total 49727
telemt_upstream_connect_success_total 47383
telemt_upstream_connect_fail_total 2207
telemt_upstream_connect_attempts_per_request{bucket="1"} 49453
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28315
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18977
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2206
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11973
telemt_me_reconnect_attempts_total 42516
telemt_me_reconnect_success_total 33530
telemt_me_reader_eof_total 36005
telemt_me_idle_close_by_peer_total 35998
telemt_me_route_drop_no_conn_total 703287
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1630840
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3307
telemt_desync_full_logged_total 1072
telemt_desync_suppressed_total 2235
telemt_desync_frames_bucket_total{bucket="1_2"} 905
telemt_desync_frames_bucket_total{bucket="3_10"} 1343
telemt_desync_frames_bucket_total{bucket="gt_10"} 1059
telemt_pool_swap_total 140
telemt_me_writer_removed_unexpected_total 34084
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 33506
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 554
telemt_user_connections_total{user="hello"} 1635535
telemt_user_connections_current{user="hello"} 619
telemt_user_octets_from_client{user="hello"} 25176056669 (23.45 GB)
telemt_user_octets_to_client{user="hello"} 616621659674 (574.27 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 183
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 30510.9 (8h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 499228
telemt_connections_bad_total 4715
telemt_handshake_timeouts_total 5099
telemt_upstream_connect_attempt_total 6760
telemt_upstream_connect_success_total 6541
telemt_upstream_connect_fail_total 219
telemt_upstream_connect_attempts_per_request{bucket="1"} 6760
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3068
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3458
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 219
telemt_me_keepalive_timeout_total 877
telemt_me_reconnect_attempts_total 21873
telemt_me_reconnect_success_total 5009
telemt_me_reader_eof_total 5632
telemt_me_idle_close_by_peer_total 5632
telemt_me_route_drop_no_conn_total 189786
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 467432
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1359
telemt_desync_full_logged_total 433
telemt_desync_suppressed_total 926
telemt_desync_frames_bucket_total{bucket="1_2"} 427
telemt_desync_frames_bucket_total{bucket="3_10"} 535
telemt_desync_frames_bucket_total{bucket="gt_10"} 397
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 5576
telemt_me_refill_failed_total 525
telemt_me_writer_restored_same_endpoint_total 5005
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 567
telemt_user_connections_total{user="hello"} 467401
telemt_user_connections_current{user="hello"} 689
telemt_user_octets_from_client{user="hello"} 5239073964 (4.88 GB)
telemt_user_octets_to_client{user="hello"} 150063903388 (139.76 GB)
telemt_user_unique_ips_current{user="hello"} 196
telemt_user_unique_ips_recent_window{user="hello"} 93
```