# Server Metrics 2026-03-13 00:32:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 66809.4 (18h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1998362
telemt_connections_bad_total 26109
telemt_handshake_timeouts_total 21413
telemt_upstream_connect_attempt_total 13291
telemt_upstream_connect_success_total 13215
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 13291
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6826
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6350
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_timeout_total 1243
telemt_me_reconnect_attempts_total 18709
telemt_me_reconnect_success_total 9850
telemt_me_reader_eof_total 10657
telemt_me_idle_close_by_peer_total 10656
telemt_me_route_drop_no_conn_total 780055
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1859169
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8659
telemt_desync_full_logged_total 2257
telemt_desync_suppressed_total 6402
telemt_desync_frames_bucket_total{bucket="1_2"} 2287
telemt_desync_frames_bucket_total{bucket="3_10"} 3119
telemt_desync_frames_bucket_total{bucket="gt_10"} 3253
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 10264
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 9837
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 414
telemt_user_connections_total{user="hello"} 1858629
telemt_user_connections_current{user="hello"} 665
telemt_user_octets_from_client{user="hello"} 27495537032 (25.61 GB)
telemt_user_octets_to_client{user="hello"} 654408538076 (609.47 GB)
telemt_user_unique_ips_current{user="hello"} 247
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 96429.9 (26h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 823806
telemt_connections_bad_total 11754
telemt_handshake_timeouts_total 31794
telemt_upstream_connect_attempt_total 24522
telemt_upstream_connect_success_total 24493
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 24522
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12784
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11620
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3435
telemt_me_reconnect_attempts_total 18119
telemt_me_reconnect_success_total 18019
telemt_me_reader_eof_total 19181
telemt_me_idle_close_by_peer_total 19181
telemt_me_route_drop_no_conn_total 266904
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 745863
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3049
telemt_desync_full_logged_total 955
telemt_desync_suppressed_total 2094
telemt_desync_frames_bucket_total{bucket="1_2"} 1230
telemt_desync_frames_bucket_total{bucket="3_10"} 991
telemt_desync_frames_bucket_total{bucket="gt_10"} 828
telemt_pool_swap_total 98
telemt_me_writer_removed_unexpected_total 18195
telemt_me_writer_restored_same_endpoint_total 18010
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 176
telemt_user_connections_total{user="hello"} 747745
telemt_user_connections_current{user="hello"} 191
telemt_user_octets_from_client{user="hello"} 12188901804 (11.35 GB)
telemt_user_octets_to_client{user="hello"} 285256117271 (265.67 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 96429.7 (26h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1714942
telemt_connections_bad_total 8778
telemt_handshake_timeouts_total 113590
telemt_upstream_connect_attempt_total 22406
telemt_upstream_connect_success_total 22396
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 22406
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11898
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10410
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1574
telemt_me_reconnect_attempts_total 18471
telemt_me_reconnect_success_total 17210
telemt_me_reader_eof_total 18223
telemt_me_idle_close_by_peer_total 18222
telemt_me_route_drop_no_conn_total 563112
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1346075
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4979
telemt_desync_full_logged_total 1528
telemt_desync_suppressed_total 3451
telemt_desync_frames_bucket_total{bucket="1_2"} 794
telemt_desync_frames_bucket_total{bucket="3_10"} 1801
telemt_desync_frames_bucket_total{bucket="gt_10"} 2384
telemt_pool_swap_total 90
telemt_me_writer_removed_unexpected_total 17376
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 17169
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 166
telemt_user_connections_total{user="hello"} 1345678
telemt_user_connections_current{user="hello"} 325
telemt_user_octets_from_client{user="hello"} 19949027812 (18.58 GB)
telemt_user_octets_to_client{user="hello"} 489686785677 (456.06 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 96430.0 (26h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1070569
telemt_connections_bad_total 13050
telemt_handshake_timeouts_total 71776
telemt_upstream_connect_attempt_total 33705
telemt_upstream_connect_success_total 31442
telemt_upstream_connect_fail_total 2126
telemt_upstream_connect_attempts_per_request{bucket="1"} 33431
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19485
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11870
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 87
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2125
telemt_me_keepalive_timeout_total 11262
telemt_me_reconnect_attempts_total 28591
telemt_me_reconnect_success_total 20751
telemt_me_reader_eof_total 22460
telemt_me_idle_close_by_peer_total 22453
telemt_me_route_drop_no_conn_total 378440
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 920244
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1892
telemt_desync_full_logged_total 627
telemt_desync_suppressed_total 1265
telemt_desync_frames_bucket_total{bucket="1_2"} 521
telemt_desync_frames_bucket_total{bucket="3_10"} 743
telemt_desync_frames_bucket_total{bucket="gt_10"} 628
telemt_pool_swap_total 83
telemt_me_writer_removed_unexpected_total 21123
telemt_me_refill_failed_total 241
telemt_me_writer_restored_same_endpoint_total 20729
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 2298
telemt_me_writer_removed_unexpected_minus_restored_total 372
telemt_user_connections_total{user="hello"} 925436
telemt_user_connections_current{user="hello"} 232
telemt_user_octets_from_client{user="hello"} 14392272645 (13.40 GB)
telemt_user_octets_to_client{user="hello"} 366606199562 (341.43 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 99
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 96429.9 (26h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1182829
telemt_connections_bad_total 12578
telemt_handshake_timeouts_total 9309
telemt_upstream_connect_attempt_total 29185
telemt_upstream_connect_success_total 28820
telemt_upstream_connect_fail_total 365
telemt_upstream_connect_attempts_per_request{bucket="1"} 29185
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14674
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13985
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 365
telemt_me_keepalive_timeout_total 1827
telemt_me_reconnect_attempts_total 35031
telemt_me_reconnect_success_total 23988
telemt_me_reader_eof_total 25252
telemt_me_idle_close_by_peer_total 25252
telemt_me_seq_mismatch_total 35
telemt_me_route_drop_no_conn_total 443481
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1091716
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 39
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4103
telemt_desync_full_logged_total 1446
telemt_desync_suppressed_total 2657
telemt_desync_frames_bucket_total{bucket="1_2"} 1209
telemt_desync_frames_bucket_total{bucket="3_10"} 1370
telemt_desync_frames_bucket_total{bucket="gt_10"} 1524
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 24611
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 23942
telemt_me_writer_restored_fallback_total 46
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 623
telemt_user_connections_total{user="hello"} 1091573
telemt_user_connections_current{user="hello"} 310
telemt_user_octets_from_client{user="hello"} 13637361316 (12.70 GB)
telemt_user_octets_to_client{user="hello"} 380655920712 (354.51 GB)
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 56
```