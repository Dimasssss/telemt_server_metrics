# Server Metrics 2026-03-11 05:10:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 53001.8 (14h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1028173
telemt_connections_bad_total 11311
telemt_handshake_timeouts_total 33755
telemt_upstream_connect_attempt_total 11335
telemt_upstream_connect_success_total 11326
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 11335
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5684
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5581
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 539
telemt_me_reconnect_attempts_total 20318
telemt_me_reconnect_success_total 8641
telemt_me_reader_eof_total 9409
telemt_me_idle_close_by_peer_total 9409
telemt_me_route_drop_no_conn_total 382476
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 924676
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4221
telemt_desync_full_logged_total 1192
telemt_desync_suppressed_total 3029
telemt_desync_frames_bucket_total{bucket="1_2"} 1183
telemt_desync_frames_bucket_total{bucket="3_10"} 1590
telemt_desync_frames_bucket_total{bucket="gt_10"} 1448
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 9084
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 8635
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 443
telemt_user_connections_total{user="hello"} 924383
telemt_user_connections_current{user="hello"} 1001
telemt_user_octets_from_client{user="hello"} 12398236456 (11.55 GB)
telemt_user_octets_to_client{user="hello"} 270604497660 (252.02 GB)
telemt_user_unique_ips_current{user="hello"} 279
telemt_user_unique_ips_recent_window{user="hello"} 159
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 53058.5 (14h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 400815
telemt_connections_bad_total 2767
telemt_handshake_timeouts_total 19340
telemt_upstream_connect_attempt_total 19779
telemt_upstream_connect_success_total 16875
telemt_upstream_connect_fail_total 2904
telemt_upstream_connect_attempts_per_request{bucket="1"} 19779
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7528
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7104
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2904
telemt_me_keepalive_timeout_total 1786
telemt_me_reconnect_attempts_total 12095
telemt_me_reconnect_success_total 11275
telemt_me_reader_eof_total 11903
telemt_me_idle_close_by_peer_total 11901
telemt_me_route_drop_no_conn_total 189685
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 344513
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1854
telemt_desync_full_logged_total 553
telemt_desync_suppressed_total 1301
telemt_desync_frames_bucket_total{bucket="1_2"} 576
telemt_desync_frames_bucket_total{bucket="3_10"} 667
telemt_desync_frames_bucket_total{bucket="gt_10"} 611
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 11407
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 11254
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 132
telemt_user_connections_total{user="hello"} 346785
telemt_user_connections_current{user="hello"} 261
telemt_user_octets_from_client{user="hello"} 3339842554 (3.11 GB)
telemt_user_octets_to_client{user="hello"} 83031439720 (77.33 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 53058.3 (14h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 683276
telemt_connections_bad_total 5766
telemt_handshake_timeouts_total 37302
telemt_upstream_connect_attempt_total 14299
telemt_upstream_connect_success_total 14113
telemt_upstream_connect_fail_total 186
telemt_upstream_connect_attempts_per_request{bucket="1"} 14299
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7688
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6345
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 80
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 186
telemt_me_keepalive_timeout_total 570
telemt_me_reconnect_attempts_total 21458
telemt_me_reconnect_success_total 10386
telemt_me_reader_eof_total 11231
telemt_me_idle_close_by_peer_total 11231
telemt_me_route_drop_no_conn_total 230412
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 609717
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1681
telemt_desync_full_logged_total 497
telemt_desync_suppressed_total 1184
telemt_desync_frames_bucket_total{bucket="1_2"} 371
telemt_desync_frames_bucket_total{bucket="3_10"} 588
telemt_desync_frames_bucket_total{bucket="gt_10"} 722
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 10870
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 10375
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 484
telemt_user_connections_total{user="hello"} 610577
telemt_user_connections_current{user="hello"} 468
telemt_user_octets_from_client{user="hello"} 7487944185 (6.97 GB)
telemt_user_octets_to_client{user="hello"} 182337297025 (169.81 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 167
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 53058.8 (14h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 521097
telemt_connections_bad_total 49894
telemt_handshake_timeouts_total 54527
telemt_upstream_connect_attempt_total 15237
telemt_upstream_connect_success_total 15237
telemt_upstream_connect_attempts_per_request{bucket="1"} 15237
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8558
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6676
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 491
telemt_me_reconnect_attempts_total 13629
telemt_me_reconnect_success_total 12586
telemt_me_reader_eof_total 13364
telemt_me_idle_close_by_peer_total 13364
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 154022
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 402317
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 855
telemt_desync_full_logged_total 350
telemt_desync_suppressed_total 505
telemt_desync_frames_bucket_total{bucket="1_2"} 319
telemt_desync_frames_bucket_total{bucket="3_10"} 309
telemt_desync_frames_bucket_total{bucket="gt_10"} 227
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 12733
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 12565
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 147
telemt_user_connections_total{user="hello"} 401956
telemt_user_connections_current{user="hello"} 401
telemt_user_octets_from_client{user="hello"} 4891135828 (4.56 GB)
telemt_user_octets_to_client{user="hello"} 110099978052 (102.54 GB)
telemt_user_unique_ips_current{user="hello"} 114
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 53058.5 (14h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 544076
telemt_connections_bad_total 5831
telemt_handshake_timeouts_total 3604
telemt_upstream_connect_attempt_total 15208
telemt_upstream_connect_success_total 15146
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 15208
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7726
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7292
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 126
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_timeout_total 559
telemt_me_reconnect_attempts_total 16237
telemt_me_reconnect_success_total 12455
telemt_me_reader_eof_total 13149
telemt_me_idle_close_by_peer_total 13149
telemt_me_route_drop_no_conn_total 176827
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 496321
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2429
telemt_desync_full_logged_total 951
telemt_desync_suppressed_total 1478
telemt_desync_frames_bucket_total{bucket="1_2"} 893
telemt_desync_frames_bucket_total{bucket="3_10"} 1032
telemt_desync_frames_bucket_total{bucket="gt_10"} 504
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 12732
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 12455
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 277
telemt_user_connections_total{user="hello"} 495939
telemt_user_connections_current{user="hello"} 512
telemt_user_octets_from_client{user="hello"} 8996866776 (8.38 GB)
telemt_user_octets_to_client{user="hello"} 174892858008 (162.88 GB)
telemt_user_unique_ips_current{user="hello"} 148
telemt_user_unique_ips_recent_window{user="hello"} 85
```