# Server Metrics 2026-03-10 19:05:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 16681.6 (4h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 535231
telemt_connections_bad_total 7985
telemt_handshake_timeouts_total 3053
telemt_upstream_connect_attempt_total 3368
telemt_upstream_connect_success_total 3359
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 3368
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1617
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1693
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 297
telemt_me_reconnect_attempts_total 12912
telemt_me_reconnect_success_total 2453
telemt_me_reader_eof_total 2775
telemt_me_idle_close_by_peer_total 2775
telemt_me_route_drop_no_conn_total 223683
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 505323
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2652
telemt_desync_full_logged_total 722
telemt_desync_suppressed_total 1930
telemt_desync_frames_bucket_total{bucket="1_2"} 704
telemt_desync_frames_bucket_total{bucket="3_10"} 1019
telemt_desync_frames_bucket_total{bucket="gt_10"} 929
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 2790
telemt_me_refill_failed_total 326
telemt_me_writer_restored_same_endpoint_total 2447
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 337
telemt_user_connections_total{user="hello"} 505233
telemt_user_connections_current{user="hello"} 1196
telemt_user_octets_from_client{user="hello"} 7489792720 (6.98 GB)
telemt_user_octets_to_client{user="hello"} 146247959140 (136.20 GB)
telemt_user_unique_ips_current{user="hello"} 333
telemt_user_unique_ips_recent_window{user="hello"} 151
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 16738.4 (4h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 233341
telemt_connections_bad_total 1815
telemt_handshake_timeouts_total 16440
telemt_upstream_connect_attempt_total 8649
telemt_upstream_connect_success_total 5905
telemt_upstream_connect_fail_total 2744
telemt_upstream_connect_attempts_per_request{bucket="1"} 8649
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1974
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1891
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 165
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1875
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2744
telemt_me_keepalive_timeout_total 705
telemt_me_reconnect_attempts_total 3821
telemt_me_reconnect_success_total 3037
telemt_me_reader_eof_total 3164
telemt_me_idle_close_by_peer_total 3162
telemt_me_route_drop_no_conn_total 128981
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 196866
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 787
telemt_desync_full_logged_total 235
telemt_desync_suppressed_total 552
telemt_desync_frames_bucket_total{bucket="1_2"} 285
telemt_desync_frames_bucket_total{bucket="3_10"} 266
telemt_desync_frames_bucket_total{bucket="gt_10"} 236
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 3092
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 3016
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 198823
telemt_user_connections_current{user="hello"} 553
telemt_user_octets_from_client{user="hello"} 2142225438 (2.00 GB)
telemt_user_octets_to_client{user="hello"} 47411859146 (44.16 GB)
telemt_user_msgs_from_client{user="hello"} 5318
telemt_user_msgs_to_client{user="hello"} 5495
telemt_user_unique_ips_current{user="hello"} 136
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 16738.2 (4h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 387296
telemt_connections_bad_total 1244
telemt_handshake_timeouts_total 31952
telemt_upstream_connect_attempt_total 5192
telemt_upstream_connect_success_total 5111
telemt_upstream_connect_fail_total 81
telemt_upstream_connect_attempts_per_request{bucket="1"} 5192
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3035
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2041
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 81
telemt_me_keepalive_timeout_total 108
telemt_me_reconnect_attempts_total 6621
telemt_me_reconnect_success_total 3173
telemt_me_reader_eof_total 3388
telemt_me_idle_close_by_peer_total 3388
telemt_me_route_drop_no_conn_total 130440
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 329407
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1048
telemt_desync_full_logged_total 295
telemt_desync_suppressed_total 753
telemt_desync_frames_bucket_total{bucket="1_2"} 257
telemt_desync_frames_bucket_total{bucket="3_10"} 351
telemt_desync_frames_bucket_total{bucket="gt_10"} 440
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 3338
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 3162
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 165
telemt_user_connections_total{user="hello"} 330361
telemt_user_connections_current{user="hello"} 670
telemt_user_octets_from_client{user="hello"} 4608970701 (4.29 GB)
telemt_user_octets_to_client{user="hello"} 105963703121 (98.69 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 212
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 16738.6 (4h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 252398
telemt_connections_bad_total 16493
telemt_handshake_timeouts_total 22625
telemt_upstream_connect_attempt_total 4595
telemt_upstream_connect_success_total 4595
telemt_upstream_connect_attempts_per_request{bucket="1"} 4595
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2454
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2140
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 93
telemt_me_reconnect_attempts_total 4724
telemt_me_reconnect_success_total 3710
telemt_me_reader_eof_total 3867
telemt_me_idle_close_by_peer_total 3867
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 82908
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 202590
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 545
telemt_desync_full_logged_total 215
telemt_desync_suppressed_total 330
telemt_desync_frames_bucket_total{bucket="1_2"} 188
telemt_desync_frames_bucket_total{bucket="3_10"} 192
telemt_desync_frames_bucket_total{bucket="gt_10"} 165
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 3780
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 3697
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 202380
telemt_user_connections_current{user="hello"} 449
telemt_user_octets_from_client{user="hello"} 2984586304 (2.78 GB)
telemt_user_octets_to_client{user="hello"} 58559770728 (54.54 GB)
telemt_user_unique_ips_current{user="hello"} 136
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 16738.2 (4h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 266894
telemt_connections_bad_total 802
telemt_handshake_timeouts_total 1827
telemt_upstream_connect_attempt_total 5063
telemt_upstream_connect_success_total 5045
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 5063
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2587
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2385
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 98
telemt_me_reconnect_attempts_total 4175
telemt_me_reconnect_success_total 4142
telemt_me_reader_eof_total 4263
telemt_me_idle_close_by_peer_total 4263
telemt_me_route_drop_no_conn_total 99015
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 252062
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1404
telemt_desync_full_logged_total 506
telemt_desync_suppressed_total 898
telemt_desync_frames_bucket_total{bucket="1_2"} 558
telemt_desync_frames_bucket_total{bucket="3_10"} 588
telemt_desync_frames_bucket_total{bucket="gt_10"} 258
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 4197
telemt_me_writer_restored_same_endpoint_total 4142
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 251994
telemt_user_connections_current{user="hello"} 664
telemt_user_octets_from_client{user="hello"} 5253434372 (4.89 GB)
telemt_user_octets_to_client{user="hello"} 79629482660 (74.16 GB)
telemt_user_unique_ips_current{user="hello"} 164
telemt_user_unique_ips_recent_window{user="hello"} 80
```