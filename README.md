# Server Metrics 2026-03-11 17:24:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 97057.2 (26h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2444635
telemt_connections_bad_total 46086
telemt_handshake_timeouts_total 54621
telemt_upstream_connect_attempt_total 20392
telemt_upstream_connect_success_total 20380
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 20392
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10281
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10001
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 5108
telemt_me_reconnect_attempts_total 33355
telemt_me_reconnect_success_total 15478
telemt_me_reader_eof_total 16766
telemt_me_idle_close_by_peer_total 16766
telemt_me_route_drop_no_conn_total 909259
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2235015
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11491
telemt_desync_full_logged_total 3154
telemt_desync_suppressed_total 8337
telemt_desync_frames_bucket_total{bucket="1_2"} 2834
telemt_desync_frames_bucket_total{bucket="3_10"} 4441
telemt_desync_frames_bucket_total{bucket="gt_10"} 4216
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 16208
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 15472
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 730
telemt_user_connections_total{user="hello"} 2233462
telemt_user_connections_current{user="hello"} 1254
telemt_user_octets_from_client{user="hello"} 30395512532 (28.31 GB)
telemt_user_octets_to_client{user="hello"} 629405765528 (586.18 GB)
telemt_user_unique_ips_current{user="hello"} 364
telemt_user_unique_ips_recent_window{user="hello"} 182
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 97113.8 (26h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 916237
telemt_connections_bad_total 16323
telemt_handshake_timeouts_total 76866
telemt_upstream_connect_attempt_total 30561
telemt_upstream_connect_success_total 27600
telemt_upstream_connect_fail_total 2961
telemt_upstream_connect_attempts_per_request{bucket="1"} 30561
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12964
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12387
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2040
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2961
telemt_me_keepalive_timeout_total 2669
telemt_me_reconnect_attempts_total 21884
telemt_me_reconnect_success_total 19780
telemt_me_reader_eof_total 20916
telemt_me_idle_close_by_peer_total 20913
telemt_me_route_drop_no_conn_total 348574
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 767048
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3036
telemt_desync_full_logged_total 967
telemt_desync_suppressed_total 2069
telemt_desync_frames_bucket_total{bucket="1_2"} 920
telemt_desync_frames_bucket_total{bucket="3_10"} 1090
telemt_desync_frames_bucket_total{bucket="gt_10"} 1026
telemt_pool_swap_total 77
telemt_me_writer_removed_unexpected_total 20055
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 19757
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 275
telemt_user_connections_total{user="hello"} 769509
telemt_user_connections_current{user="hello"} 534
telemt_user_octets_from_client{user="hello"} 9177709906 (8.55 GB)
telemt_user_octets_to_client{user="hello"} 218149104688 (203.17 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 97113.8 (26h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1567547
telemt_connections_bad_total 9538
telemt_handshake_timeouts_total 126968
telemt_upstream_connect_attempt_total 25190
telemt_upstream_connect_success_total 24869
telemt_upstream_connect_fail_total 321
telemt_upstream_connect_attempts_per_request{bucket="1"} 25190
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13370
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11371
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 127
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 321
telemt_me_keepalive_timeout_total 1779
telemt_me_reconnect_attempts_total 43558
telemt_me_reconnect_success_total 18900
telemt_me_reader_eof_total 20497
telemt_me_idle_close_by_peer_total 20497
telemt_me_route_drop_no_conn_total 572021
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1370530
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3635
telemt_desync_full_logged_total 1065
telemt_desync_suppressed_total 2570
telemt_desync_frames_bucket_total{bucket="1_2"} 888
telemt_desync_frames_bucket_total{bucket="3_10"} 1380
telemt_desync_frames_bucket_total{bucket="gt_10"} 1367
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 19932
telemt_me_refill_failed_total 765
telemt_me_writer_restored_same_endpoint_total 18888
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 1032
telemt_user_connections_total{user="hello"} 1370220
telemt_user_connections_current{user="hello"} 881
telemt_user_octets_from_client{user="hello"} 16912751321 (15.75 GB)
telemt_user_octets_to_client{user="hello"} 416448546865 (387.85 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 241
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 97114.3 (26h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1122859
telemt_connections_bad_total 77987
telemt_handshake_timeouts_total 106515
telemt_upstream_connect_attempt_total 26122
telemt_upstream_connect_success_total 26122
telemt_upstream_connect_attempts_per_request{bucket="1"} 26122
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14263
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11854
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1190
telemt_me_reconnect_attempts_total 23421
telemt_me_reconnect_success_total 21283
telemt_me_reader_eof_total 22564
telemt_me_idle_close_by_peer_total 22563
telemt_me_seq_mismatch_total 22
telemt_me_route_drop_no_conn_total 371169
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 904907
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 33
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1902
telemt_desync_full_logged_total 724
telemt_desync_suppressed_total 1178
telemt_desync_frames_bucket_total{bucket="1_2"} 680
telemt_desync_frames_bucket_total{bucket="3_10"} 670
telemt_desync_frames_bucket_total{bucket="gt_10"} 552
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 21576
telemt_me_refill_failed_total 64
telemt_me_writer_restored_same_endpoint_total 21251
telemt_me_writer_restored_fallback_total 32
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 293
telemt_user_connections_total{user="hello"} 904184
telemt_user_connections_current{user="hello"} 559
telemt_user_octets_from_client{user="hello"} 10849036112 (10.10 GB)
telemt_user_octets_to_client{user="hello"} 275525820436 (256.60 GB)
telemt_user_unique_ips_current{user="hello"} 156
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 1790.3 (0h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33804
telemt_connections_bad_total 14
telemt_handshake_timeouts_total 194
telemt_upstream_connect_attempt_total 401
telemt_upstream_connect_success_total 401
telemt_upstream_connect_attempts_per_request{bucket="1"} 401
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 243
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 154
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 287
telemt_me_reconnect_success_total 286
telemt_me_reader_eof_total 249
telemt_me_idle_close_by_peer_total 249
telemt_me_route_drop_no_conn_total 10162
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 31507
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 76
telemt_desync_full_logged_total 28
telemt_desync_suppressed_total 48
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 17
telemt_desync_frames_bucket_total{bucket="gt_10"} 38
telemt_me_writer_removed_unexpected_total 272
telemt_me_writer_restored_same_endpoint_total 264
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 256
telemt_user_connections_total{user="hello"} 31508
telemt_user_connections_current{user="hello"} 577
telemt_user_octets_from_client{user="hello"} 2733008524 (2.55 GB)
telemt_user_octets_to_client{user="hello"} 8437166420 (7.86 GB)
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 87
```