# Server Metrics 2026-03-15 17:39:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 69900.4 (19h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2455114
telemt_connections_bad_total 148835
telemt_handshake_timeouts_total 31655
telemt_upstream_connect_attempt_total 13600
telemt_upstream_connect_success_total 13541
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 13600
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7028
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6447
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 14943
telemt_me_reconnect_success_total 10046
telemt_me_reader_eof_total 10739
telemt_me_idle_close_by_peer_total 10739
telemt_me_route_drop_no_conn_total 846946
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2049637
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8011
telemt_desync_full_logged_total 2170
telemt_desync_suppressed_total 5841
telemt_desync_frames_bucket_total{bucket="1_2"} 1945
telemt_desync_frames_bucket_total{bucket="3_10"} 3077
telemt_desync_frames_bucket_total{bucket="gt_10"} 2989
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 10369
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 10035
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 323
telemt_user_connections_total{user="hello"} 2049126
telemt_user_connections_current{user="hello"} 2275
telemt_user_octets_from_client{user="hello"} 30338889056 (28.26 GB)
telemt_user_octets_to_client{user="hello"} 777699072480 (724.29 GB)
telemt_user_unique_ips_current{user="hello"} 697
telemt_user_unique_ips_recent_window{user="hello"} 283
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 69901.2 (19h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 948861
telemt_connections_bad_total 51323
telemt_handshake_timeouts_total 62495
telemt_upstream_connect_attempt_total 17484
telemt_upstream_connect_success_total 17390
telemt_upstream_connect_fail_total 94
telemt_upstream_connect_attempts_per_request{bucket="1"} 17484
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9244
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7974
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 40
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 132
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 94
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 14744
telemt_me_reconnect_success_total 13536
telemt_me_reader_eof_total 14318
telemt_me_idle_close_by_peer_total 14318
telemt_me_route_drop_no_conn_total 245193
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 733965
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2190
telemt_desync_full_logged_total 737
telemt_desync_suppressed_total 1453
telemt_desync_frames_bucket_total{bucket="1_2"} 776
telemt_desync_frames_bucket_total{bucket="3_10"} 826
telemt_desync_frames_bucket_total{bucket="gt_10"} 588
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 13749
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 13524
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 213
telemt_user_connections_total{user="hello"} 734199
telemt_user_connections_current{user="hello"} 882
telemt_user_octets_from_client{user="hello"} 10709767767 (9.97 GB)
telemt_user_octets_to_client{user="hello"} 276964993764 (257.94 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 250
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 69901.3 (19h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2113549
telemt_connections_bad_total 50144
telemt_handshake_timeouts_total 213818
telemt_upstream_connect_attempt_total 15120
telemt_upstream_connect_success_total 15047
telemt_upstream_connect_fail_total 73
telemt_upstream_connect_attempts_per_request{bucket="1"} 15120
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7765
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 12789
telemt_me_reconnect_success_total 11520
telemt_me_reader_eof_total 12205
telemt_me_idle_close_by_peer_total 12205
telemt_me_route_drop_no_conn_total 547736
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1307381
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3345
telemt_desync_full_logged_total 1207
telemt_desync_suppressed_total 2138
telemt_desync_frames_bucket_total{bucket="1_2"} 763
telemt_desync_frames_bucket_total{bucket="3_10"} 1304
telemt_desync_frames_bucket_total{bucket="gt_10"} 1278
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 11722
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 11501
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 202
telemt_user_connections_total{user="hello"} 1303307
telemt_user_connections_current{user="hello"} 1312
telemt_user_octets_from_client{user="hello"} 22132854468 (20.61 GB)
telemt_user_octets_to_client{user="hello"} 472037187048 (439.62 GB)
telemt_user_unique_ips_current{user="hello"} 414
telemt_user_unique_ips_recent_window{user="hello"} 185
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 69901.2 (19h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1016484
telemt_connections_bad_total 82046
telemt_handshake_timeouts_total 49348
telemt_upstream_connect_attempt_total 170475
telemt_upstream_connect_success_total 169891
telemt_upstream_connect_fail_total 584
telemt_upstream_connect_attempts_per_request{bucket="1"} 170475
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 156662
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13170
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 584
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 61488
telemt_me_reconnect_success_total 13424
telemt_me_reader_eof_total 15285
telemt_me_idle_close_by_peer_total 15285
telemt_me_seq_mismatch_total 27
telemt_me_route_drop_no_conn_total 238203
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 634585
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 44
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1796
telemt_desync_full_logged_total 488
telemt_desync_suppressed_total 1308
telemt_desync_frames_bucket_total{bucket="1_2"} 460
telemt_desync_frames_bucket_total{bucket="3_10"} 697
telemt_desync_frames_bucket_total{bucket="gt_10"} 639
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 15068
telemt_me_refill_failed_total 1504
telemt_me_writer_restored_same_endpoint_total 13388
telemt_me_writer_restored_fallback_total 36
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1644
telemt_user_connections_total{user="hello"} 787104
telemt_user_connections_current{user="hello"} 920
telemt_user_octets_from_client{user="hello"} 14572897073 (13.57 GB)
telemt_user_octets_to_client{user="hello"} 281331126112 (262.01 GB)
telemt_user_msgs_from_client{user="hello"} 3035962
telemt_user_msgs_to_client{user="hello"} 10927629
telemt_user_unique_ips_current{user="hello"} 259
telemt_user_unique_ips_recent_window{user="hello"} 128
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 69902.0 (19h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1029074
telemt_connections_bad_total 12185
telemt_handshake_timeouts_total 23048
telemt_upstream_connect_attempt_total 15408
telemt_upstream_connect_success_total 15325
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 15408
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7097
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_timeout_total 88
telemt_me_reconnect_attempts_total 15515
telemt_me_reconnect_success_total 11820
telemt_me_reader_eof_total 12609
telemt_me_idle_close_by_peer_total 12609
telemt_me_route_drop_no_conn_total 256415
telemt_me_route_drop_channel_closed_total 29
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 851951
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2866
telemt_desync_full_logged_total 963
telemt_desync_suppressed_total 1903
telemt_desync_frames_bucket_total{bucket="1_2"} 879
telemt_desync_frames_bucket_total{bucket="3_10"} 1068
telemt_desync_frames_bucket_total{bucket="gt_10"} 919
telemt_pool_swap_total 58
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 12079
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 11812
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 259
telemt_user_connections_total{user="hello"} 851979
telemt_user_connections_current{user="hello"} 1059
telemt_user_octets_from_client{user="hello"} 10647944384 (9.92 GB)
telemt_user_octets_to_client{user="hello"} 299427183284 (278.86 GB)
telemt_user_unique_ips_current{user="hello"} 255
telemt_user_unique_ips_recent_window{user="hello"} 116
```