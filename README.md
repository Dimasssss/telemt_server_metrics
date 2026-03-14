# Server Metrics 2026-03-14 02:29:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 160250.1 (44h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4670155
telemt_connections_bad_total 39818
telemt_handshake_timeouts_total 108437
telemt_upstream_connect_attempt_total 33853
telemt_upstream_connect_success_total 33627
telemt_upstream_connect_fail_total 226
telemt_upstream_connect_attempts_per_request{bucket="1"} 33853
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18353
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15128
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 146
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 226
telemt_me_keepalive_timeout_total 6714
telemt_me_reconnect_attempts_total 33452
telemt_me_reconnect_success_total 23311
telemt_me_reader_eof_total 24999
telemt_me_idle_close_by_peer_total 24998
telemt_me_route_drop_no_conn_total 1767542
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4282160
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16756
telemt_desync_full_logged_total 4519
telemt_desync_suppressed_total 12237
telemt_desync_frames_bucket_total{bucket="1_2"} 4186
telemt_desync_frames_bucket_total{bucket="3_10"} 6394
telemt_desync_frames_bucket_total{bucket="gt_10"} 6176
telemt_pool_swap_total 137
telemt_me_writer_removed_unexpected_total 23963
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 23298
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 652
telemt_user_connections_total{user="hello"} 4284013
telemt_user_connections_current{user="hello"} 572
telemt_user_octets_from_client{user="hello"} 62903302232 (58.58 GB)
telemt_user_octets_to_client{user="hello"} 1354067725941 (1.23 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 210
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 59915.5 (16h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 696557
telemt_connections_bad_total 50961
telemt_handshake_timeouts_total 13109
telemt_upstream_connect_attempt_total 16785
telemt_upstream_connect_success_total 16533
telemt_upstream_connect_fail_total 252
telemt_upstream_connect_attempts_per_request{bucket="1"} 16785
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9223
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7069
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 212
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 252
telemt_me_keepalive_timeout_total 2060
telemt_me_reconnect_attempts_total 14954
telemt_me_reconnect_success_total 11510
telemt_me_reader_eof_total 12217
telemt_me_idle_close_by_peer_total 12216
telemt_me_route_drop_no_conn_total 234182
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 557494
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1681
telemt_desync_full_logged_total 460
telemt_desync_suppressed_total 1221
telemt_desync_frames_bucket_total{bucket="1_2"} 360
telemt_desync_frames_bucket_total{bucket="3_10"} 730
telemt_desync_frames_bucket_total{bucket="gt_10"} 591
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 11776
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 11502
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 266
telemt_user_connections_total{user="hello"} 559445
telemt_user_connections_current{user="hello"} 190
telemt_user_octets_from_client{user="hello"} 5975987221 (5.57 GB)
telemt_user_octets_to_client{user="hello"} 179872911872 (167.52 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 189870.4 (52h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3376064
telemt_connections_bad_total 34965
telemt_handshake_timeouts_total 223299
telemt_upstream_connect_attempt_total 42712
telemt_upstream_connect_success_total 42691
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 42712
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22425
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20028
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 231
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10420
telemt_me_reconnect_attempts_total 37907
telemt_me_reconnect_success_total 32946
telemt_me_reader_eof_total 34984
telemt_me_idle_close_by_peer_total 34983
telemt_me_route_drop_no_conn_total 1157386
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2809436
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9338
telemt_desync_full_logged_total 3119
telemt_desync_suppressed_total 6219
telemt_desync_frames_bucket_total{bucket="1_2"} 1609
telemt_desync_frames_bucket_total{bucket="3_10"} 3377
telemt_desync_frames_bucket_total{bucket="gt_10"} 4352
telemt_pool_swap_total 178
telemt_me_writer_removed_unexpected_total 33409
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 32905
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 463
telemt_user_connections_total{user="hello"} 2808661
telemt_user_connections_current{user="hello"} 352
telemt_user_octets_from_client{user="hello"} 45176925572 (42.07 GB)
telemt_user_octets_to_client{user="hello"} 1004666028621 (935.67 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 127
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 189873.0 (52h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2254488
telemt_connections_bad_total 22967
telemt_handshake_timeouts_total 246187
telemt_upstream_connect_attempt_total 59475
telemt_upstream_connect_success_total 57013
telemt_upstream_connect_fail_total 2325
telemt_upstream_connect_attempts_per_request{bucket="1"} 59201
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34074
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22773
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2324
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20420
telemt_me_reconnect_attempts_total 49590
telemt_me_reconnect_success_total 40558
telemt_me_reader_eof_total 43487
telemt_me_idle_close_by_peer_total 43480
telemt_me_route_drop_no_conn_total 771382
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1799418
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3806
telemt_desync_full_logged_total 1223
telemt_desync_suppressed_total 2583
telemt_desync_frames_bucket_total{bucket="1_2"} 1012
telemt_desync_frames_bucket_total{bucket="3_10"} 1588
telemt_desync_frames_bucket_total{bucket="gt_10"} 1206
telemt_pool_swap_total 166
telemt_me_writer_removed_unexpected_total 41190
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 40534
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 632
telemt_user_connections_total{user="hello"} 1805345
telemt_user_connections_current{user="hello"} 159
telemt_user_octets_from_client{user="hello"} 27588277323 (25.69 GB)
telemt_user_octets_to_client{user="hello"} 666378128882 (620.61 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 59306.4 (16h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 696715
telemt_connections_bad_total 7908
telemt_handshake_timeouts_total 8662
telemt_upstream_connect_attempt_total 14989
telemt_upstream_connect_success_total 14577
telemt_upstream_connect_fail_total 412
telemt_upstream_connect_attempts_per_request{bucket="1"} 14989
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7017
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7535
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 412
telemt_me_keepalive_timeout_total 1502
telemt_me_reconnect_attempts_total 43784
telemt_me_reconnect_success_total 11621
telemt_me_reader_eof_total 12931
telemt_me_idle_close_by_peer_total 12930
telemt_me_route_drop_no_conn_total 264466
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 648828
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1688
telemt_desync_full_logged_total 528
telemt_desync_suppressed_total 1160
telemt_desync_frames_bucket_total{bucket="1_2"} 504
telemt_desync_frames_bucket_total{bucket="3_10"} 656
telemt_desync_frames_bucket_total{bucket="gt_10"} 528
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 12729
telemt_me_refill_failed_total 1001
telemt_me_writer_restored_same_endpoint_total 11616
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1108
telemt_user_connections_total{user="hello"} 648714
telemt_user_connections_current{user="hello"} 265
telemt_user_octets_from_client{user="hello"} 11889372412 (11.07 GB)
telemt_user_octets_to_client{user="hello"} 211199369824 (196.69 GB)
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 31
```