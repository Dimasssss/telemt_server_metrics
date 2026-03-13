# Server Metrics 2026-03-13 10:08:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 101398.3 (28h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2924555
telemt_connections_bad_total 36440
telemt_handshake_timeouts_total 52688
telemt_upstream_connect_attempt_total 20010
telemt_upstream_connect_success_total 19901
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 20010
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10228
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9622
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_timeout_total 1423
telemt_me_reconnect_attempts_total 24931
telemt_me_reconnect_success_total 14862
telemt_me_reader_eof_total 16008
telemt_me_idle_close_by_peer_total 16007
telemt_me_route_drop_no_conn_total 1079987
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2666272
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11628
telemt_desync_full_logged_total 3011
telemt_desync_suppressed_total 8617
telemt_desync_frames_bucket_total{bucket="1_2"} 2983
telemt_desync_frames_bucket_total{bucket="3_10"} 4356
telemt_desync_frames_bucket_total{bucket="gt_10"} 4289
telemt_pool_swap_total 83
telemt_me_writer_removed_unexpected_total 15383
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 14849
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 521
telemt_user_connections_total{user="hello"} 2666164
telemt_user_connections_current{user="hello"} 1716
telemt_user_octets_from_client{user="hello"} 36755941072 (34.23 GB)
telemt_user_octets_to_client{user="hello"} 867413520724 (807.84 GB)
telemt_user_unique_ips_current{user="hello"} 448
telemt_user_unique_ips_recent_window{user="hello"} 257
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 131018.9 (36h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1178463
telemt_connections_bad_total 14952
telemt_handshake_timeouts_total 106906
telemt_upstream_connect_attempt_total 32432
telemt_upstream_connect_success_total 32401
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 32432
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16694
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15617
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 3754
telemt_me_reconnect_attempts_total 24381
telemt_me_reconnect_success_total 24254
telemt_me_reader_eof_total 25855
telemt_me_idle_close_by_peer_total 25855
telemt_me_route_drop_no_conn_total 363978
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1014270
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4470
telemt_desync_full_logged_total 1354
telemt_desync_suppressed_total 3116
telemt_desync_frames_bucket_total{bucket="1_2"} 1626
telemt_desync_frames_bucket_total{bucket="3_10"} 1479
telemt_desync_frames_bucket_total{bucket="gt_10"} 1365
telemt_pool_swap_total 135
telemt_me_writer_removed_unexpected_total 24492
telemt_me_writer_restored_same_endpoint_total 24245
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 238
telemt_user_connections_total{user="hello"} 1016205
telemt_user_connections_current{user="hello"} 372
telemt_user_octets_from_client{user="hello"} 15445063080 (14.38 GB)
telemt_user_octets_to_client{user="hello"} 370337620463 (344.90 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 118
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 131018.7 (36h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2272898
telemt_connections_bad_total 25073
telemt_handshake_timeouts_total 155228
telemt_upstream_connect_attempt_total 29975
telemt_upstream_connect_success_total 29965
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 29975
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15706
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14139
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 115
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1852
telemt_me_reconnect_attempts_total 24384
telemt_me_reconnect_success_total 23096
telemt_me_reader_eof_total 24467
telemt_me_idle_close_by_peer_total 24466
telemt_me_route_drop_no_conn_total 743515
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1821181
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6004
telemt_desync_full_logged_total 1918
telemt_desync_suppressed_total 4086
telemt_desync_frames_bucket_total{bucket="1_2"} 978
telemt_desync_frames_bucket_total{bucket="3_10"} 2189
telemt_desync_frames_bucket_total{bucket="gt_10"} 2837
telemt_pool_swap_total 123
telemt_me_writer_removed_unexpected_total 23326
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 23055
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 230
telemt_user_connections_total{user="hello"} 1820631
telemt_user_connections_current{user="hello"} 1066
telemt_user_octets_from_client{user="hello"} 31591070960 (29.42 GB)
telemt_user_octets_to_client{user="hello"} 655785089761 (610.75 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 296
telemt_user_unique_ips_recent_window{user="hello"} 176
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 131019.2 (36h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1438183
telemt_connections_bad_total 14236
telemt_handshake_timeouts_total 89528
telemt_upstream_connect_attempt_total 42942
telemt_upstream_connect_success_total 40634
telemt_upstream_connect_fail_total 2171
telemt_upstream_connect_attempts_per_request{bucket="1"} 42668
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24719
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15824
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2170
telemt_me_keepalive_timeout_total 11503
telemt_me_reconnect_attempts_total 37208
telemt_me_reconnect_success_total 28260
telemt_me_reader_eof_total 30427
telemt_me_idle_close_by_peer_total 30420
telemt_me_route_drop_no_conn_total 507627
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1201473
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2256
telemt_desync_full_logged_total 744
telemt_desync_suppressed_total 1512
telemt_desync_frames_bucket_total{bucket="1_2"} 626
telemt_desync_frames_bucket_total{bucket="3_10"} 863
telemt_desync_frames_bucket_total{bucket="gt_10"} 767
telemt_pool_swap_total 114
telemt_me_writer_removed_unexpected_total 28744
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 28236
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 484
telemt_user_connections_total{user="hello"} 1206231
telemt_user_connections_current{user="hello"} 658
telemt_user_octets_from_client{user="hello"} 18295422561 (17.04 GB)
telemt_user_octets_to_client{user="hello"} 479229119014 (446.32 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 184
telemt_user_unique_ips_recent_window{user="hello"} 115
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 131018.9 (36h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1609553
telemt_connections_bad_total 36072
telemt_handshake_timeouts_total 13094
telemt_upstream_connect_attempt_total 41988
telemt_upstream_connect_success_total 41489
telemt_upstream_connect_fail_total 499
telemt_upstream_connect_attempts_per_request{bucket="1"} 41988
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20884
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20391
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 198
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 499
telemt_me_keepalive_timeout_total 2297
telemt_me_reconnect_attempts_total 52946
telemt_me_reconnect_success_total 34969
telemt_me_reader_eof_total 36748
telemt_me_idle_close_by_peer_total 36748
telemt_me_seq_mismatch_total 48
telemt_me_route_drop_no_conn_total 589245
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1464087
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 52
telemt_me_hardswap_pending_ttl_expired_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 5140
telemt_desync_full_logged_total 1832
telemt_desync_suppressed_total 3308
telemt_desync_frames_bucket_total{bucket="1_2"} 1585
telemt_desync_frames_bucket_total{bucket="3_10"} 1664
telemt_desync_frames_bucket_total{bucket="gt_10"} 1891
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 35910
telemt_me_refill_failed_total 557
telemt_me_writer_restored_same_endpoint_total 34908
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 941
telemt_user_connections_total{user="hello"} 1463884
telemt_user_connections_current{user="hello"} 739
telemt_user_octets_from_client{user="hello"} 18712492324 (17.43 GB)
telemt_user_octets_to_client{user="hello"} 510929561336 (475.84 GB)
telemt_user_unique_ips_current{user="hello"} 197
telemt_user_unique_ips_recent_window{user="hello"} 84
```