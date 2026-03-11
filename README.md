# Server Metrics 2026-03-11 01:26:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 39590.0 (10h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 812598
telemt_connections_bad_total 9523
telemt_handshake_timeouts_total 10011
telemt_upstream_connect_attempt_total 8588
telemt_upstream_connect_success_total 8579
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 8588
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4288
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4232
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 482
telemt_me_reconnect_attempts_total 18219
telemt_me_reconnect_success_total 6552
telemt_me_reader_eof_total 7171
telemt_me_idle_close_by_peer_total 7171
telemt_me_route_drop_no_conn_total 331666
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 769121
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3598
telemt_desync_full_logged_total 1013
telemt_desync_suppressed_total 2585
telemt_desync_frames_bucket_total{bucket="1_2"} 1054
telemt_desync_frames_bucket_total{bucket="3_10"} 1340
telemt_desync_frames_bucket_total{bucket="gt_10"} 1204
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 6971
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 6546
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 419
telemt_user_connections_total{user="hello"} 768881
telemt_user_connections_current{user="hello"} 428
telemt_user_octets_from_client{user="hello"} 10586866780 (9.86 GB)
telemt_user_octets_to_client{user="hello"} 233997500848 (217.93 GB)
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 39646.8 (11h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 349525
telemt_connections_bad_total 2407
telemt_handshake_timeouts_total 17861
telemt_upstream_connect_attempt_total 15808
telemt_upstream_connect_success_total 12923
telemt_upstream_connect_fail_total 2885
telemt_upstream_connect_attempts_per_request{bucket="1"} 15808
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5630
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5052
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2032
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2885
telemt_me_keepalive_timeout_total 1716
telemt_me_reconnect_attempts_total 8781
telemt_me_reconnect_success_total 7965
telemt_me_reader_eof_total 8410
telemt_me_idle_close_by_peer_total 8408
telemt_me_route_drop_no_conn_total 174247
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 298555
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1780
telemt_desync_full_logged_total 510
telemt_desync_suppressed_total 1270
telemt_desync_frames_bucket_total{bucket="1_2"} 545
telemt_desync_frames_bucket_total{bucket="3_10"} 633
telemt_desync_frames_bucket_total{bucket="gt_10"} 602
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 8073
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 7944
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 108
telemt_user_connections_total{user="hello"} 300824
telemt_user_connections_current{user="hello"} 151
telemt_user_octets_from_client{user="hello"} 2862631670 (2.67 GB)
telemt_user_octets_to_client{user="hello"} 71184447340 (66.30 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 39646.6 (11h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 581080
telemt_connections_bad_total 4181
telemt_handshake_timeouts_total 34250
telemt_upstream_connect_attempt_total 10766
telemt_upstream_connect_success_total 10619
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 10766
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5948
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4604
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 517
telemt_me_reconnect_attempts_total 18598
telemt_me_reconnect_success_total 7535
telemt_me_reader_eof_total 8210
telemt_me_idle_close_by_peer_total 8210
telemt_me_route_drop_no_conn_total 198625
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 514012
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
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 7984
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 7524
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 449
telemt_user_connections_total{user="hello"} 514926
telemt_user_connections_current{user="hello"} 186
telemt_user_octets_from_client{user="hello"} 6917529045 (6.44 GB)
telemt_user_octets_to_client{user="hello"} 156152570429 (145.43 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 39646.9 (11h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 430216
telemt_connections_bad_total 37622
telemt_handshake_timeouts_total 40880
telemt_upstream_connect_attempt_total 11400
telemt_upstream_connect_success_total 11400
telemt_upstream_connect_attempts_per_request{bucket="1"} 11400
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6426
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4972
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 420
telemt_me_reconnect_attempts_total 10424
telemt_me_reconnect_success_total 9389
telemt_me_reader_eof_total 9932
telemt_me_idle_close_by_peer_total 9932
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 130530
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 338251
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 727
telemt_desync_full_logged_total 291
telemt_desync_suppressed_total 436
telemt_desync_frames_bucket_total{bucket="1_2"} 279
telemt_desync_frames_bucket_total{bucket="3_10"} 252
telemt_desync_frames_bucket_total{bucket="gt_10"} 196
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 9509
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 9371
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 120
telemt_user_connections_total{user="hello"} 337925
telemt_user_connections_current{user="hello"} 147
telemt_user_octets_from_client{user="hello"} 4241993864 (3.95 GB)
telemt_user_octets_to_client{user="hello"} 91994105996 (85.68 GB)
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 39646.7 (11h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 454092
telemt_connections_bad_total 5179
telemt_handshake_timeouts_total 2942
telemt_upstream_connect_attempt_total 11845
telemt_upstream_connect_success_total 11795
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 11845
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6103
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5576
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 114
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 513
telemt_me_reconnect_attempts_total 13519
telemt_me_reconnect_success_total 9751
telemt_me_reader_eof_total 10260
telemt_me_idle_close_by_peer_total 10260
telemt_me_route_drop_no_conn_total 149872
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 416324
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2286
telemt_desync_full_logged_total 886
telemt_desync_suppressed_total 1400
telemt_desync_frames_bucket_total{bucket="1_2"} 845
telemt_desync_frames_bucket_total{bucket="3_10"} 973
telemt_desync_frames_bucket_total{bucket="gt_10"} 468
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 9994
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 9751
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 243
telemt_user_connections_total{user="hello"} 416026
telemt_user_connections_current{user="hello"} 254
telemt_user_octets_from_client{user="hello"} 8398557976 (7.82 GB)
telemt_user_octets_to_client{user="hello"} 147932519216 (137.77 GB)
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 35
```