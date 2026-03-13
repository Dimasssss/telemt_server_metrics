# Server Metrics 2026-03-13 02:09:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 72619.7 (20h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2066622
telemt_connections_bad_total 26947
telemt_handshake_timeouts_total 22017
telemt_upstream_connect_attempt_total 14390
telemt_upstream_connect_success_total 14307
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 14390
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7370
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6896
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_timeout_total 1262
telemt_me_reconnect_attempts_total 19542
telemt_me_reconnect_success_total 10681
telemt_me_reader_eof_total 11540
telemt_me_idle_close_by_peer_total 11539
telemt_me_route_drop_no_conn_total 802248
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1915623
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8701
telemt_desync_full_logged_total 2265
telemt_desync_suppressed_total 6436
telemt_desync_frames_bucket_total{bucket="1_2"} 2293
telemt_desync_frames_bucket_total{bucket="3_10"} 3138
telemt_desync_frames_bucket_total{bucket="gt_10"} 3270
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 11108
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 10668
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 427
telemt_user_connections_total{user="hello"} 1915080
telemt_user_connections_current{user="hello"} 623
telemt_user_octets_from_client{user="hello"} 28012539832 (26.09 GB)
telemt_user_octets_to_client{user="hello"} 668032872036 (622.15 GB)
telemt_user_unique_ips_current{user="hello"} 224
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 102240.1 (28h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 848328
telemt_connections_bad_total 11794
telemt_handshake_timeouts_total 32082
telemt_upstream_connect_attempt_total 26032
telemt_upstream_connect_success_total 26003
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 26032
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13518
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12396
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3451
telemt_me_reconnect_attempts_total 19371
telemt_me_reconnect_success_total 19264
telemt_me_reader_eof_total 20518
telemt_me_idle_close_by_peer_total 20518
telemt_me_route_drop_no_conn_total 273026
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 769369
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3088
telemt_desync_full_logged_total 970
telemt_desync_suppressed_total 2118
telemt_desync_frames_bucket_total{bucket="1_2"} 1253
telemt_desync_frames_bucket_total{bucket="3_10"} 1002
telemt_desync_frames_bucket_total{bucket="gt_10"} 833
telemt_pool_swap_total 104
telemt_me_writer_removed_unexpected_total 19452
telemt_me_writer_restored_same_endpoint_total 19255
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 188
telemt_user_connections_total{user="hello"} 771272
telemt_user_connections_current{user="hello"} 199
telemt_user_octets_from_client{user="hello"} 12309847904 (11.46 GB)
telemt_user_octets_to_client{user="hello"} 291021734271 (271.04 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 102240.0 (28h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1760742
telemt_connections_bad_total 9165
telemt_handshake_timeouts_total 118141
telemt_upstream_connect_attempt_total 23850
telemt_upstream_connect_success_total 23840
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 23850
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12565
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11182
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 88
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1596
telemt_me_reconnect_attempts_total 19654
telemt_me_reconnect_success_total 18391
telemt_me_reader_eof_total 19475
telemt_me_idle_close_by_peer_total 19474
telemt_me_route_drop_no_conn_total 575300
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1384271
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5005
telemt_desync_full_logged_total 1535
telemt_desync_suppressed_total 3470
telemt_desync_frames_bucket_total{bucket="1_2"} 798
telemt_desync_frames_bucket_total{bucket="3_10"} 1812
telemt_desync_frames_bucket_total{bucket="gt_10"} 2395
telemt_pool_swap_total 95
telemt_me_writer_removed_unexpected_total 18565
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 18350
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 174
telemt_user_connections_total{user="hello"} 1383867
telemt_user_connections_current{user="hello"} 299
telemt_user_octets_from_client{user="hello"} 20150684208 (18.77 GB)
telemt_user_octets_to_client{user="hello"} 500090530737 (465.75 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 127
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 102240.1 (28h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1101477
telemt_connections_bad_total 13133
telemt_handshake_timeouts_total 72952
telemt_upstream_connect_attempt_total 35793
telemt_upstream_connect_success_total 33521
telemt_upstream_connect_fail_total 2135
telemt_upstream_connect_attempts_per_request{bucket="1"} 35519
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20784
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12648
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2134
telemt_me_keepalive_timeout_total 11281
telemt_me_reconnect_attempts_total 31483
telemt_me_reconnect_success_total 22560
telemt_me_reader_eof_total 24380
telemt_me_idle_close_by_peer_total 24373
telemt_me_route_drop_no_conn_total 390554
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 944307
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1895
telemt_desync_full_logged_total 628
telemt_desync_suppressed_total 1267
telemt_desync_frames_bucket_total{bucket="1_2"} 522
telemt_desync_frames_bucket_total{bucket="3_10"} 743
telemt_desync_frames_bucket_total{bucket="gt_10"} 630
telemt_pool_swap_total 86
telemt_me_writer_removed_unexpected_total 22990
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 22537
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 2298
telemt_me_writer_removed_unexpected_minus_restored_total 430
telemt_user_connections_total{user="hello"} 949489
telemt_user_connections_current{user="hello"} 223
telemt_user_octets_from_client{user="hello"} 14508150521 (13.51 GB)
telemt_user_octets_to_client{user="hello"} 372122437646 (346.57 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 102240.3 (28h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1215700
telemt_connections_bad_total 12602
telemt_handshake_timeouts_total 9499
telemt_upstream_connect_attempt_total 32119
telemt_upstream_connect_success_total 31725
telemt_upstream_connect_fail_total 394
telemt_upstream_connect_attempts_per_request{bucket="1"} 32119
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16214
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15336
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 162
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 394
telemt_me_keepalive_timeout_total 1875
telemt_me_reconnect_attempts_total 39085
telemt_me_reconnect_success_total 26628
telemt_me_reader_eof_total 27975
telemt_me_idle_close_by_peer_total 27975
telemt_me_seq_mismatch_total 37
telemt_me_route_drop_no_conn_total 455108
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1123658
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 41
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4187
telemt_desync_full_logged_total 1486
telemt_desync_suppressed_total 2701
telemt_desync_frames_bucket_total{bucket="1_2"} 1256
telemt_desync_frames_bucket_total{bucket="3_10"} 1385
telemt_desync_frames_bucket_total{bucket="gt_10"} 1546
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 27322
telemt_me_refill_failed_total 386
telemt_me_writer_restored_same_endpoint_total 26580
telemt_me_writer_restored_fallback_total 48
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 694
telemt_user_connections_total{user="hello"} 1123513
telemt_user_connections_current{user="hello"} 312
telemt_user_octets_from_client{user="hello"} 13788865536 (12.84 GB)
telemt_user_octets_to_client{user="hello"} 387364251876 (360.76 GB)
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 34
```