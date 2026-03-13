# Server Metrics 2026-03-13 04:57:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 82718.0 (22h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2232414
telemt_connections_bad_total 31834
telemt_handshake_timeouts_total 23480
telemt_upstream_connect_attempt_total 16297
telemt_upstream_connect_success_total 16207
telemt_upstream_connect_fail_total 90
telemt_upstream_connect_attempts_per_request{bucket="1"} 16297
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8354
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7808
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 90
telemt_me_keepalive_timeout_total 1305
telemt_me_reconnect_attempts_total 20968
telemt_me_reconnect_success_total 12102
telemt_me_reader_eof_total 13058
telemt_me_idle_close_by_peer_total 13057
telemt_me_route_drop_no_conn_total 850803
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2052763
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9042
telemt_desync_full_logged_total 2343
telemt_desync_suppressed_total 6699
telemt_desync_frames_bucket_total{bucket="1_2"} 2371
telemt_desync_frames_bucket_total{bucket="3_10"} 3279
telemt_desync_frames_bucket_total{bucket="gt_10"} 3392
telemt_pool_swap_total 67
telemt_me_writer_removed_unexpected_total 12547
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 12089
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 445
telemt_user_connections_total{user="hello"} 2052186
telemt_user_connections_current{user="hello"} 996
telemt_user_octets_from_client{user="hello"} 29875974664 (27.82 GB)
telemt_user_octets_to_client{user="hello"} 708985330276 (660.29 GB)
telemt_user_unique_ips_current{user="hello"} 313
telemt_user_unique_ips_recent_window{user="hello"} 137
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 112338.5 (31h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 906689
telemt_connections_bad_total 12313
telemt_handshake_timeouts_total 39767
telemt_upstream_connect_attempt_total 28456
telemt_upstream_connect_success_total 28425
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 28456
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14703
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13632
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 3531
telemt_me_reconnect_attempts_total 21319
telemt_me_reconnect_success_total 21202
telemt_me_reader_eof_total 22598
telemt_me_idle_close_by_peer_total 22598
telemt_me_route_drop_no_conn_total 288444
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 817535
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3248
telemt_desync_full_logged_total 1022
telemt_desync_suppressed_total 2226
telemt_desync_frames_bucket_total{bucket="1_2"} 1296
telemt_desync_frames_bucket_total{bucket="3_10"} 1062
telemt_desync_frames_bucket_total{bucket="gt_10"} 890
telemt_pool_swap_total 115
telemt_me_writer_removed_unexpected_total 21411
telemt_me_writer_restored_same_endpoint_total 21193
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 209
telemt_user_connections_total{user="hello"} 819434
telemt_user_connections_current{user="hello"} 374
telemt_user_octets_from_client{user="hello"} 13160968344 (12.26 GB)
telemt_user_octets_to_client{user="hello"} 314704888283 (293.09 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 118
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 112338.4 (31h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1870962
telemt_connections_bad_total 17800
telemt_handshake_timeouts_total 123001
telemt_upstream_connect_attempt_total 26141
telemt_upstream_connect_success_total 26131
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 26141
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13707
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12319
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1642
telemt_me_reconnect_attempts_total 21469
telemt_me_reconnect_success_total 20201
telemt_me_reader_eof_total 21393
telemt_me_idle_close_by_peer_total 21392
telemt_me_route_drop_no_conn_total 603425
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1477521
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5143
telemt_desync_full_logged_total 1574
telemt_desync_suppressed_total 3569
telemt_desync_frames_bucket_total{bucket="1_2"} 828
telemt_desync_frames_bucket_total{bucket="3_10"} 1857
telemt_desync_frames_bucket_total{bucket="gt_10"} 2458
telemt_pool_swap_total 105
telemt_me_writer_removed_unexpected_total 20393
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 20160
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 192
telemt_user_connections_total{user="hello"} 1477057
telemt_user_connections_current{user="hello"} 507
telemt_user_octets_from_client{user="hello"} 25468266720 (23.72 GB)
telemt_user_octets_to_client{user="hello"} 523295936701 (487.36 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 184
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 112338.7 (31h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1155591
telemt_connections_bad_total 13211
telemt_handshake_timeouts_total 75082
telemt_upstream_connect_attempt_total 38557
telemt_upstream_connect_success_total 36273
telemt_upstream_connect_fail_total 2147
telemt_upstream_connect_attempts_per_request{bucket="1"} 38283
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22353
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13829
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2146
telemt_me_keepalive_timeout_total 11391
telemt_me_reconnect_attempts_total 33761
telemt_me_reconnect_success_total 24827
telemt_me_reader_eof_total 26792
telemt_me_idle_close_by_peer_total 26785
telemt_me_route_drop_no_conn_total 411215
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 994788
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1964
telemt_desync_full_logged_total 646
telemt_desync_suppressed_total 1318
telemt_desync_frames_bucket_total{bucket="1_2"} 543
telemt_desync_frames_bucket_total{bucket="3_10"} 766
telemt_desync_frames_bucket_total{bucket="gt_10"} 655
telemt_pool_swap_total 97
telemt_me_writer_removed_unexpected_total 25275
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 24803
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 448
telemt_user_connections_total{user="hello"} 999965
telemt_user_connections_current{user="hello"} 321
telemt_user_octets_from_client{user="hello"} 15279368533 (14.23 GB)
telemt_user_octets_to_client{user="hello"} 393861585926 (366.81 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 112338.8 (31h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1287457
telemt_connections_bad_total 12915
telemt_handshake_timeouts_total 10296
telemt_upstream_connect_attempt_total 35395
telemt_upstream_connect_success_total 34969
telemt_upstream_connect_fail_total 426
telemt_upstream_connect_attempts_per_request{bucket="1"} 35395
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17847
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16933
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 174
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 426
telemt_me_keepalive_timeout_total 1943
telemt_me_reconnect_attempts_total 43126
telemt_me_reconnect_success_total 29394
telemt_me_reader_eof_total 30893
telemt_me_idle_close_by_peer_total 30893
telemt_me_seq_mismatch_total 39
telemt_me_route_drop_no_conn_total 476419
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1191678
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 43
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4333
telemt_desync_full_logged_total 1561
telemt_desync_suppressed_total 2772
telemt_desync_frames_bucket_total{bucket="1_2"} 1311
telemt_desync_frames_bucket_total{bucket="3_10"} 1413
telemt_desync_frames_bucket_total{bucket="gt_10"} 1609
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 30156
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 29343
telemt_me_writer_restored_fallback_total 51
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 762
telemt_user_connections_total{user="hello"} 1191533
telemt_user_connections_current{user="hello"} 526
telemt_user_octets_from_client{user="hello"} 14471067960 (13.48 GB)
telemt_user_octets_to_client{user="hello"} 405809652836 (377.94 GB)
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 69
```