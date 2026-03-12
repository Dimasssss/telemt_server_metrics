# Server Metrics 2026-03-12 22:29:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 59469.5 (16h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1918556
telemt_connections_bad_total 26062
telemt_handshake_timeouts_total 21024
telemt_upstream_connect_attempt_total 11707
telemt_upstream_connect_success_total 11639
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 11707
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6062
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5540
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 600
telemt_me_reconnect_attempts_total 17498
telemt_me_reconnect_success_total 8642
telemt_me_reader_eof_total 9335
telemt_me_idle_close_by_peer_total 9334
telemt_me_route_drop_no_conn_total 749593
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1785171
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8494
telemt_desync_full_logged_total 2212
telemt_desync_suppressed_total 6282
telemt_desync_frames_bucket_total{bucket="1_2"} 2237
telemt_desync_frames_bucket_total{bucket="3_10"} 3058
telemt_desync_frames_bucket_total{bucket="gt_10"} 3199
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 9041
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 8629
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 399
telemt_user_connections_total{user="hello"} 1784644
telemt_user_connections_current{user="hello"} 577
telemt_user_octets_from_client{user="hello"} 26946747260 (25.10 GB)
telemt_user_octets_to_client{user="hello"} 635416325628 (591.78 GB)
telemt_user_unique_ips_current{user="hello"} 213
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 89090.1 (24h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 795346
telemt_connections_bad_total 11706
telemt_handshake_timeouts_total 31300
telemt_upstream_connect_attempt_total 22495
telemt_upstream_connect_success_total 22466
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 22495
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11818
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10559
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3411
telemt_me_reconnect_attempts_total 16480
telemt_me_reconnect_success_total 16384
telemt_me_reader_eof_total 17433
telemt_me_idle_close_by_peer_total 17433
telemt_me_route_drop_no_conn_total 257396
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 718445
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3001
telemt_desync_full_logged_total 933
telemt_desync_suppressed_total 2068
telemt_desync_frames_bucket_total{bucket="1_2"} 1188
telemt_desync_frames_bucket_total{bucket="3_10"} 986
telemt_desync_frames_bucket_total{bucket="gt_10"} 827
telemt_pool_swap_total 89
telemt_me_writer_removed_unexpected_total 16552
telemt_me_writer_restored_same_endpoint_total 16375
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 168
telemt_user_connections_total{user="hello"} 720325
telemt_user_connections_current{user="hello"} 206
telemt_user_octets_from_client{user="hello"} 12068782300 (11.24 GB)
telemt_user_octets_to_client{user="hello"} 279100610795 (259.93 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 89090.1 (24h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1654024
telemt_connections_bad_total 7866
telemt_handshake_timeouts_total 113274
telemt_upstream_connect_attempt_total 20732
telemt_upstream_connect_success_total 20726
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 20732
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11095
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9554
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 1221
telemt_me_reconnect_attempts_total 17186
telemt_me_reconnect_success_total 15936
telemt_me_reader_eof_total 16841
telemt_me_idle_close_by_peer_total 16840
telemt_me_route_drop_no_conn_total 544026
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1287678
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4968
telemt_desync_full_logged_total 1524
telemt_desync_suppressed_total 3444
telemt_desync_frames_bucket_total{bucket="1_2"} 790
telemt_desync_frames_bucket_total{bucket="3_10"} 1796
telemt_desync_frames_bucket_total{bucket="gt_10"} 2382
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 16088
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 15895
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 152
telemt_user_connections_total{user="hello"} 1287284
telemt_user_connections_current{user="hello"} 341
telemt_user_octets_from_client{user="hello"} 19713838560 (18.36 GB)
telemt_user_octets_to_client{user="hello"} 475101317249 (442.47 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 89090.3 (24h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1018939
telemt_connections_bad_total 13000
telemt_handshake_timeouts_total 71390
telemt_upstream_connect_attempt_total 22770
telemt_upstream_connect_success_total 22677
telemt_upstream_connect_fail_total 93
telemt_upstream_connect_attempts_per_request{bucket="1"} 22770
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12750
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 93
telemt_me_keepalive_timeout_total 1689
telemt_me_reconnect_attempts_total 25980
telemt_me_reconnect_success_total 18250
telemt_me_reader_eof_total 19490
telemt_me_idle_close_by_peer_total 19490
telemt_me_route_drop_no_conn_total 364446
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 887829
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1852
telemt_desync_full_logged_total 613
telemt_desync_suppressed_total 1239
telemt_desync_frames_bucket_total{bucket="1_2"} 514
telemt_desync_frames_bucket_total{bucket="3_10"} 722
telemt_desync_frames_bucket_total{bucket="gt_10"} 616
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 18636
telemt_me_refill_failed_total 239
telemt_me_writer_restored_same_endpoint_total 18229
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 386
telemt_user_connections_total{user="hello"} 887175
telemt_user_connections_current{user="hello"} 237
telemt_user_octets_from_client{user="hello"} 14196423436 (13.22 GB)
telemt_user_octets_to_client{user="hello"} 354298305580 (329.97 GB)
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 89090.3 (24h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1139824
telemt_connections_bad_total 12536
telemt_handshake_timeouts_total 9200
telemt_upstream_connect_attempt_total 27252
telemt_upstream_connect_success_total 26914
telemt_upstream_connect_fail_total 338
telemt_upstream_connect_attempts_per_request{bucket="1"} 27252
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13767
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12996
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 140
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 338
telemt_me_keepalive_timeout_total 1445
telemt_me_reconnect_attempts_total 33513
telemt_me_reconnect_success_total 22474
telemt_me_reader_eof_total 23629
telemt_me_idle_close_by_peer_total 23629
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 426521
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1049451
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3933
telemt_desync_full_logged_total 1368
telemt_desync_suppressed_total 2565
telemt_desync_frames_bucket_total{bucket="1_2"} 1154
telemt_desync_frames_bucket_total{bucket="3_10"} 1297
telemt_desync_frames_bucket_total{bucket="gt_10"} 1482
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 23079
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 22430
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 605
telemt_user_connections_total{user="hello"} 1049310
telemt_user_connections_current{user="hello"} 239
telemt_user_octets_from_client{user="hello"} 12871151632 (11.99 GB)
telemt_user_octets_to_client{user="hello"} 372943404340 (347.33 GB)
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 38
```