# Server Metrics 2026-03-11 02:17:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 42637.4 (11h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 840065
telemt_connections_bad_total 10043
telemt_handshake_timeouts_total 13073
telemt_upstream_connect_attempt_total 9294
telemt_upstream_connect_success_total 9285
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 9294
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4641
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4585
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 495
telemt_me_reconnect_attempts_total 18751
telemt_me_reconnect_success_total 7082
telemt_me_reader_eof_total 7744
telemt_me_idle_close_by_peer_total 7744
telemt_me_route_drop_no_conn_total 339112
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 792612
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3656
telemt_desync_full_logged_total 1029
telemt_desync_suppressed_total 2627
telemt_desync_frames_bucket_total{bucket="1_2"} 1069
telemt_desync_frames_bucket_total{bucket="3_10"} 1367
telemt_desync_frames_bucket_total{bucket="gt_10"} 1220
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 7507
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 7076
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 425
telemt_user_connections_total{user="hello"} 792348
telemt_user_connections_current{user="hello"} 451
telemt_user_octets_from_client{user="hello"} 10778528112 (10.04 GB)
telemt_user_octets_to_client{user="hello"} 238217003688 (221.86 GB)
telemt_user_unique_ips_current{user="hello"} 164
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 42694.2 (11h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 358261
telemt_connections_bad_total 2413
telemt_handshake_timeouts_total 18057
telemt_upstream_connect_attempt_total 16866
telemt_upstream_connect_success_total 13976
telemt_upstream_connect_fail_total 2890
telemt_upstream_connect_attempts_per_request{bucket="1"} 16866
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6124
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5611
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2032
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2890
telemt_me_keepalive_timeout_total 1738
telemt_me_reconnect_attempts_total 9675
telemt_me_reconnect_success_total 8858
telemt_me_reader_eof_total 9354
telemt_me_idle_close_by_peer_total 9352
telemt_me_route_drop_no_conn_total 176465
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 306893
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1787
telemt_desync_full_logged_total 513
telemt_desync_suppressed_total 1274
telemt_desync_frames_bucket_total{bucket="1_2"} 547
telemt_desync_frames_bucket_total{bucket="3_10"} 637
telemt_desync_frames_bucket_total{bucket="gt_10"} 603
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 8971
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 8837
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 113
telemt_user_connections_total{user="hello"} 309163
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 2904092522 (2.70 GB)
telemt_user_octets_to_client{user="hello"} 72630104116 (67.64 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 42693.9 (11h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 596846
telemt_connections_bad_total 4904
telemt_handshake_timeouts_total 34415
telemt_upstream_connect_attempt_total 11679
telemt_upstream_connect_success_total 11523
telemt_upstream_connect_fail_total 156
telemt_upstream_connect_attempts_per_request{bucket="1"} 11679
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6373
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5078
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 156
telemt_me_keepalive_timeout_total 533
telemt_me_reconnect_attempts_total 19344
telemt_me_reconnect_success_total 8278
telemt_me_reader_eof_total 8999
telemt_me_idle_close_by_peer_total 8999
telemt_me_route_drop_no_conn_total 202865
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 528791
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1539
telemt_desync_full_logged_total 447
telemt_desync_suppressed_total 1092
telemt_desync_frames_bucket_total{bucket="1_2"} 344
telemt_desync_frames_bucket_total{bucket="3_10"} 533
telemt_desync_frames_bucket_total{bucket="gt_10"} 662
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 8736
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 8267
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 458
telemt_user_connections_total{user="hello"} 529698
telemt_user_connections_current{user="hello"} 211
telemt_user_octets_from_client{user="hello"} 6980436149 (6.50 GB)
telemt_user_octets_to_client{user="hello"} 161469705993 (150.38 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 42694.3 (11h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 445875
telemt_connections_bad_total 40436
telemt_handshake_timeouts_total 42993
telemt_upstream_connect_attempt_total 12417
telemt_upstream_connect_success_total 12417
telemt_upstream_connect_attempts_per_request{bucket="1"} 12417
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6986
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5428
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 432
telemt_me_reconnect_attempts_total 11285
telemt_me_reconnect_success_total 10248
telemt_me_reader_eof_total 10861
telemt_me_idle_close_by_peer_total 10861
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 133914
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 348884
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 758
telemt_desync_full_logged_total 302
telemt_desync_suppressed_total 456
telemt_desync_frames_bucket_total{bucket="1_2"} 287
telemt_desync_frames_bucket_total{bucket="3_10"} 265
telemt_desync_frames_bucket_total{bucket="gt_10"} 206
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 10372
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 10229
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 124
telemt_user_connections_total{user="hello"} 348553
telemt_user_connections_current{user="hello"} 191
telemt_user_octets_from_client{user="hello"} 4315158244 (4.02 GB)
telemt_user_octets_to_client{user="hello"} 93632600848 (87.20 GB)
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 42694.1 (11h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 470419
telemt_connections_bad_total 5790
telemt_handshake_timeouts_total 2999
telemt_upstream_connect_attempt_total 12624
telemt_upstream_connect_success_total 12571
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 12624
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6492
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5963
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 114
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_keepalive_timeout_total 525
telemt_me_reconnect_attempts_total 14138
telemt_me_reconnect_success_total 10365
telemt_me_reader_eof_total 10926
telemt_me_idle_close_by_peer_total 10926
telemt_me_route_drop_no_conn_total 152986
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 429508
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2305
telemt_desync_full_logged_total 896
telemt_desync_suppressed_total 1409
telemt_desync_frames_bucket_total{bucket="1_2"} 856
telemt_desync_frames_bucket_total{bucket="3_10"} 978
telemt_desync_frames_bucket_total{bucket="gt_10"} 471
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 10618
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 10365
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 253
telemt_user_connections_total{user="hello"} 429184
telemt_user_connections_current{user="hello"} 236
telemt_user_octets_from_client{user="hello"} 8464608192 (7.88 GB)
telemt_user_octets_to_client{user="hello"} 152012599160 (141.57 GB)
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 27
```