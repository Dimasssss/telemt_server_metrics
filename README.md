# Server Metrics 2026-03-11 06:26:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 57574.6 (15h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1135941
telemt_connections_bad_total 13234
telemt_handshake_timeouts_total 38443
telemt_upstream_connect_attempt_total 12126
telemt_upstream_connect_success_total 12117
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 12126
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6085
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5970
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 691
telemt_me_reconnect_attempts_total 20892
telemt_me_reconnect_success_total 9210
telemt_me_reader_eof_total 10016
telemt_me_idle_close_by_peer_total 10016
telemt_me_route_drop_no_conn_total 417404
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1020929
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4790
telemt_desync_full_logged_total 1342
telemt_desync_suppressed_total 3448
telemt_desync_frames_bucket_total{bucket="1_2"} 1316
telemt_desync_frames_bucket_total{bucket="3_10"} 1798
telemt_desync_frames_bucket_total{bucket="gt_10"} 1676
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 9662
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 9204
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 452
telemt_user_connections_total{user="hello"} 1020597
telemt_user_connections_current{user="hello"} 1099
telemt_user_octets_from_client{user="hello"} 13543688440 (12.61 GB)
telemt_user_octets_to_client{user="hello"} 300281314264 (279.66 GB)
telemt_user_unique_ips_current{user="hello"} 300
telemt_user_unique_ips_recent_window{user="hello"} 169
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 57631.5 (16h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 436673
telemt_connections_bad_total 4788
telemt_handshake_timeouts_total 21459
telemt_upstream_connect_attempt_total 20816
telemt_upstream_connect_success_total 17908
telemt_upstream_connect_fail_total 2908
telemt_upstream_connect_attempts_per_request{bucket="1"} 20816
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8034
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7631
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2908
telemt_me_keepalive_timeout_total 2011
telemt_me_reconnect_attempts_total 12906
telemt_me_reconnect_success_total 12081
telemt_me_reader_eof_total 12769
telemt_me_idle_close_by_peer_total 12767
telemt_me_route_drop_no_conn_total 199247
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 373737
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1932
telemt_desync_full_logged_total 579
telemt_desync_suppressed_total 1353
telemt_desync_frames_bucket_total{bucket="1_2"} 614
telemt_desync_frames_bucket_total{bucket="3_10"} 693
telemt_desync_frames_bucket_total{bucket="gt_10"} 625
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 12222
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 12059
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 141
telemt_user_connections_total{user="hello"} 376007
telemt_user_connections_current{user="hello"} 390
telemt_user_octets_from_client{user="hello"} 3775267758 (3.52 GB)
telemt_user_octets_to_client{user="hello"} 92874603664 (86.50 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 57631.4 (16h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 744676
telemt_connections_bad_total 6436
telemt_handshake_timeouts_total 40960
telemt_upstream_connect_attempt_total 15473
telemt_upstream_connect_success_total 15272
telemt_upstream_connect_fail_total 201
telemt_upstream_connect_attempts_per_request{bucket="1"} 15473
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8328
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6858
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 201
telemt_me_keepalive_timeout_total 694
telemt_me_reconnect_attempts_total 22395
telemt_me_reconnect_success_total 11322
telemt_me_reader_eof_total 12207
telemt_me_idle_close_by_peer_total 12207
telemt_me_route_drop_no_conn_total 251515
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 665485
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1901
telemt_desync_full_logged_total 547
telemt_desync_suppressed_total 1354
telemt_desync_frames_bucket_total{bucket="1_2"} 440
telemt_desync_frames_bucket_total{bucket="3_10"} 689
telemt_desync_frames_bucket_total{bucket="gt_10"} 772
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 11814
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 11311
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 492
telemt_user_connections_total{user="hello"} 666316
telemt_user_connections_current{user="hello"} 525
telemt_user_octets_from_client{user="hello"} 7908805385 (7.37 GB)
telemt_user_octets_to_client{user="hello"} 196782588097 (183.27 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 123
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 57631.8 (16h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 566327
telemt_connections_bad_total 54070
telemt_handshake_timeouts_total 58271
telemt_upstream_connect_attempt_total 16377
telemt_upstream_connect_success_total 16376
telemt_upstream_connect_attempts_per_request{bucket="1"} 16376
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9170
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7202
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 642
telemt_me_reconnect_attempts_total 14546
telemt_me_reconnect_success_total 13499
telemt_me_reader_eof_total 14331
telemt_me_idle_close_by_peer_total 14331
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 169926
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 438821
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 935
telemt_desync_full_logged_total 388
telemt_desync_suppressed_total 547
telemt_desync_frames_bucket_total{bucket="1_2"} 341
telemt_desync_frames_bucket_total{bucket="3_10"} 348
telemt_desync_frames_bucket_total{bucket="gt_10"} 246
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 13657
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 13477
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 158
telemt_user_connections_total{user="hello"} 438367
telemt_user_connections_current{user="hello"} 449
telemt_user_octets_from_client{user="hello"} 5291899636 (4.93 GB)
telemt_user_octets_to_client{user="hello"} 120658093276 (112.37 GB)
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 57631.5 (16h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 593484
telemt_connections_bad_total 5960
telemt_handshake_timeouts_total 4166
telemt_upstream_connect_attempt_total 16356
telemt_upstream_connect_success_total 16288
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 16356
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8348
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7807
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 131
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 675
telemt_me_reconnect_attempts_total 17082
telemt_me_reconnect_success_total 13297
telemt_me_reader_eof_total 14045
telemt_me_idle_close_by_peer_total 14045
telemt_me_route_drop_no_conn_total 194333
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 539736
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2552
telemt_desync_full_logged_total 988
telemt_desync_suppressed_total 1564
telemt_desync_frames_bucket_total{bucket="1_2"} 916
telemt_desync_frames_bucket_total{bucket="3_10"} 1091
telemt_desync_frames_bucket_total{bucket="gt_10"} 545
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 13586
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 13297
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 289
telemt_user_connections_total{user="hello"} 539469
telemt_user_connections_current{user="hello"} 558
telemt_user_octets_from_client{user="hello"} 9486689459 (8.84 GB)
telemt_user_octets_to_client{user="hello"} 191708501806 (178.54 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 171
telemt_user_unique_ips_recent_window{user="hello"} 107
```