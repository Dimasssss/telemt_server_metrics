# Server Metrics 2026-03-11 01:37:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 40199.7 (11h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 816943
telemt_connections_bad_total 9529
telemt_handshake_timeouts_total 10411
telemt_upstream_connect_attempt_total 8743
telemt_upstream_connect_success_total 8734
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 8743
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4371
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4304
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 485
telemt_me_reconnect_attempts_total 18331
telemt_me_reconnect_success_total 6664
telemt_me_reader_eof_total 7294
telemt_me_idle_close_by_peer_total 7294
telemt_me_route_drop_no_conn_total 333200
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 772969
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3614
telemt_desync_full_logged_total 1018
telemt_desync_suppressed_total 2596
telemt_desync_frames_bucket_total{bucket="1_2"} 1055
telemt_desync_frames_bucket_total{bucket="3_10"} 1346
telemt_desync_frames_bucket_total{bucket="gt_10"} 1213
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 7084
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 6658
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 420
telemt_user_connections_total{user="hello"} 772728
telemt_user_connections_current{user="hello"} 454
telemt_user_octets_from_client{user="hello"} 10613488476 (9.88 GB)
telemt_user_octets_to_client{user="hello"} 234736090160 (218.62 GB)
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 40256.4 (11h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 351187
telemt_connections_bad_total 2407
telemt_handshake_timeouts_total 17914
telemt_upstream_connect_attempt_total 16003
telemt_upstream_connect_success_total 13118
telemt_upstream_connect_fail_total 2885
telemt_upstream_connect_attempts_per_request{bucket="1"} 16003
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5715
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5162
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2032
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2885
telemt_me_keepalive_timeout_total 1719
telemt_me_reconnect_attempts_total 8948
telemt_me_reconnect_success_total 8132
telemt_me_reader_eof_total 8588
telemt_me_idle_close_by_peer_total 8586
telemt_me_route_drop_no_conn_total 174695
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 300116
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1786
telemt_desync_full_logged_total 512
telemt_desync_suppressed_total 1274
telemt_desync_frames_bucket_total{bucket="1_2"} 546
telemt_desync_frames_bucket_total{bucket="3_10"} 637
telemt_desync_frames_bucket_total{bucket="gt_10"} 603
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 8241
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 8111
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 109
telemt_user_connections_total{user="hello"} 302385
telemt_user_connections_current{user="hello"} 170
telemt_user_octets_from_client{user="hello"} 2867339886 (2.67 GB)
telemt_user_octets_to_client{user="hello"} 71581900168 (66.67 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 40256.2 (11h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 584135
telemt_connections_bad_total 4227
telemt_handshake_timeouts_total 34284
telemt_upstream_connect_attempt_total 10949
telemt_upstream_connect_success_total 10801
telemt_upstream_connect_fail_total 148
telemt_upstream_connect_attempts_per_request{bucket="1"} 10949
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6039
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4693
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 69
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 148
telemt_me_keepalive_timeout_total 519
telemt_me_reconnect_attempts_total 18751
telemt_me_reconnect_success_total 7688
telemt_me_reader_eof_total 8372
telemt_me_idle_close_by_peer_total 8372
telemt_me_route_drop_no_conn_total 199311
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 516960
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1522
telemt_desync_full_logged_total 435
telemt_desync_suppressed_total 1087
telemt_desync_frames_bucket_total{bucket="1_2"} 344
telemt_desync_frames_bucket_total{bucket="3_10"} 523
telemt_desync_frames_bucket_total{bucket="gt_10"} 655
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 8139
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 7677
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 451
telemt_user_connections_total{user="hello"} 517874
telemt_user_connections_current{user="hello"} 212
telemt_user_octets_from_client{user="hello"} 6930821757 (6.45 GB)
telemt_user_octets_to_client{user="hello"} 158285831137 (147.42 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 40256.6 (11h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 433248
telemt_connections_bad_total 38224
telemt_handshake_timeouts_total 41284
telemt_upstream_connect_attempt_total 11628
telemt_upstream_connect_success_total 11628
telemt_upstream_connect_attempts_per_request{bucket="1"} 11628
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6549
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5077
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 423
telemt_me_reconnect_attempts_total 10625
telemt_me_reconnect_success_total 9589
telemt_me_reader_eof_total 10151
telemt_me_idle_close_by_peer_total 10151
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 131094
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 340248
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 732
telemt_desync_full_logged_total 292
telemt_desync_suppressed_total 440
telemt_desync_frames_bucket_total{bucket="1_2"} 279
telemt_desync_frames_bucket_total{bucket="3_10"} 253
telemt_desync_frames_bucket_total{bucket="gt_10"} 200
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 9710
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 9571
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 121
telemt_user_connections_total{user="hello"} 339919
telemt_user_connections_current{user="hello"} 175
telemt_user_octets_from_client{user="hello"} 4252345564 (3.96 GB)
telemt_user_octets_to_client{user="hello"} 92315941840 (85.98 GB)
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 40256.4 (11h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 457474
telemt_connections_bad_total 5338
telemt_handshake_timeouts_total 2953
telemt_upstream_connect_attempt_total 12015
telemt_upstream_connect_success_total 11965
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 12015
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6181
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5668
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 114
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 514
telemt_me_reconnect_attempts_total 13660
telemt_me_reconnect_success_total 9891
telemt_me_reader_eof_total 10411
telemt_me_idle_close_by_peer_total 10411
telemt_me_route_drop_no_conn_total 150457
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 419005
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2291
telemt_desync_full_logged_total 888
telemt_desync_suppressed_total 1403
telemt_desync_frames_bucket_total{bucket="1_2"} 848
telemt_desync_frames_bucket_total{bucket="3_10"} 974
telemt_desync_frames_bucket_total{bucket="gt_10"} 469
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 10136
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 9891
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 245
telemt_user_connections_total{user="hello"} 418700
telemt_user_connections_current{user="hello"} 184
telemt_user_octets_from_client{user="hello"} 8411290508 (7.83 GB)
telemt_user_octets_to_client{user="hello"} 149646755036 (139.37 GB)
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 27
```