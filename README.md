# Server Metrics 2026-03-11 05:15:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 53306.8 (14h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1034613
telemt_connections_bad_total 11312
telemt_handshake_timeouts_total 34732
telemt_upstream_connect_attempt_total 11423
telemt_upstream_connect_success_total 11414
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 11423
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5732
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5621
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 542
telemt_me_reconnect_attempts_total 20363
telemt_me_reconnect_success_total 8686
telemt_me_reader_eof_total 9460
telemt_me_idle_close_by_peer_total 9460
telemt_me_route_drop_no_conn_total 384173
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 929912
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4235
telemt_desync_full_logged_total 1202
telemt_desync_suppressed_total 3033
telemt_desync_frames_bucket_total{bucket="1_2"} 1188
telemt_desync_frames_bucket_total{bucket="3_10"} 1595
telemt_desync_frames_bucket_total{bucket="gt_10"} 1452
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 9129
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 8680
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 443
telemt_user_connections_total{user="hello"} 929622
telemt_user_connections_current{user="hello"} 916
telemt_user_octets_from_client{user="hello"} 12459223272 (11.60 GB)
telemt_user_octets_to_client{user="hello"} 271744304256 (253.08 GB)
telemt_user_unique_ips_current{user="hello"} 258
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 53363.5 (14h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 402650
telemt_connections_bad_total 2780
telemt_handshake_timeouts_total 19366
telemt_upstream_connect_attempt_total 19901
telemt_upstream_connect_success_total 16996
telemt_upstream_connect_fail_total 2905
telemt_upstream_connect_attempts_per_request{bucket="1"} 19901
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7596
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7157
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2905
telemt_me_keepalive_timeout_total 1787
telemt_me_reconnect_attempts_total 12173
telemt_me_reconnect_success_total 11353
telemt_me_reader_eof_total 11998
telemt_me_idle_close_by_peer_total 11996
telemt_me_route_drop_no_conn_total 190258
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 346229
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1859
telemt_desync_full_logged_total 555
telemt_desync_suppressed_total 1304
telemt_desync_frames_bucket_total{bucket="1_2"} 579
telemt_desync_frames_bucket_total{bucket="3_10"} 669
telemt_desync_frames_bucket_total{bucket="gt_10"} 611
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 11485
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 11332
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 132
telemt_user_connections_total{user="hello"} 348499
telemt_user_connections_current{user="hello"} 253
telemt_user_octets_from_client{user="hello"} 3349128934 (3.12 GB)
telemt_user_octets_to_client{user="hello"} 84396707772 (78.60 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 53363.2 (14h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 687227
telemt_connections_bad_total 5766
telemt_handshake_timeouts_total 37588
telemt_upstream_connect_attempt_total 14425
telemt_upstream_connect_success_total 14233
telemt_upstream_connect_fail_total 192
telemt_upstream_connect_attempts_per_request{bucket="1"} 14425
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7749
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6403
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 81
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 192
telemt_me_keepalive_timeout_total 570
telemt_me_reconnect_attempts_total 21535
telemt_me_reconnect_success_total 10463
telemt_me_reader_eof_total 11309
telemt_me_idle_close_by_peer_total 11309
telemt_me_route_drop_no_conn_total 231623
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 613302
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1709
telemt_desync_full_logged_total 503
telemt_desync_suppressed_total 1206
telemt_desync_frames_bucket_total{bucket="1_2"} 381
telemt_desync_frames_bucket_total{bucket="3_10"} 603
telemt_desync_frames_bucket_total{bucket="gt_10"} 725
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 10948
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 10452
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 485
telemt_user_connections_total{user="hello"} 614162
telemt_user_connections_current{user="hello"} 480
telemt_user_octets_from_client{user="hello"} 7525423077 (7.01 GB)
telemt_user_octets_to_client{user="hello"} 183214958381 (170.63 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 167
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 53363.6 (14h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 523991
telemt_connections_bad_total 50172
telemt_handshake_timeouts_total 54759
telemt_upstream_connect_attempt_total 15359
telemt_upstream_connect_success_total 15359
telemt_upstream_connect_attempts_per_request{bucket="1"} 15359
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8628
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6728
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 492
telemt_me_reconnect_attempts_total 13708
telemt_me_reconnect_success_total 12665
telemt_me_reader_eof_total 13450
telemt_me_idle_close_by_peer_total 13450
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 154923
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 404675
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 865
telemt_desync_full_logged_total 353
telemt_desync_suppressed_total 512
telemt_desync_frames_bucket_total{bucket="1_2"} 319
telemt_desync_frames_bucket_total{bucket="3_10"} 314
telemt_desync_frames_bucket_total{bucket="gt_10"} 232
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 12812
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 12644
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 147
telemt_user_connections_total{user="hello"} 404313
telemt_user_connections_current{user="hello"} 342
telemt_user_octets_from_client{user="hello"} 4957567720 (4.62 GB)
telemt_user_octets_to_client{user="hello"} 111194933436 (103.56 GB)
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 53363.3 (14h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 547103
telemt_connections_bad_total 5831
telemt_handshake_timeouts_total 3642
telemt_upstream_connect_attempt_total 15314
telemt_upstream_connect_success_total 15250
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 15314
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7781
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7341
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 126
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_keepalive_timeout_total 561
telemt_me_reconnect_attempts_total 16297
telemt_me_reconnect_success_total 12515
telemt_me_reader_eof_total 13215
telemt_me_idle_close_by_peer_total 13215
telemt_me_route_drop_no_conn_total 177917
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 499216
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2434
telemt_desync_full_logged_total 953
telemt_desync_suppressed_total 1481
telemt_desync_frames_bucket_total{bucket="1_2"} 895
telemt_desync_frames_bucket_total{bucket="3_10"} 1035
telemt_desync_frames_bucket_total{bucket="gt_10"} 504
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 12792
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 12515
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 277
telemt_user_connections_total{user="hello"} 498842
telemt_user_connections_current{user="hello"} 436
telemt_user_octets_from_client{user="hello"} 9013840092 (8.39 GB)
telemt_user_octets_to_client{user="hello"} 175641359252 (163.58 GB)
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 64
```