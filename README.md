# Server Metrics 2026-03-11 01:11:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 38676.1 (10h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 805389
telemt_connections_bad_total 9523
telemt_handshake_timeouts_total 9101
telemt_upstream_connect_attempt_total 8389
telemt_upstream_connect_success_total 8380
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 8389
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4184
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4137
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 481
telemt_me_reconnect_attempts_total 18064
telemt_me_reconnect_success_total 6398
telemt_me_reader_eof_total 7006
telemt_me_idle_close_by_peer_total 7006
telemt_me_route_drop_no_conn_total 329768
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 762877
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3587
telemt_desync_full_logged_total 1007
telemt_desync_suppressed_total 2580
telemt_desync_frames_bucket_total{bucket="1_2"} 1050
telemt_desync_frames_bucket_total{bucket="3_10"} 1333
telemt_desync_frames_bucket_total{bucket="gt_10"} 1204
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 6816
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 6392
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 418
telemt_user_connections_total{user="hello"} 762638
telemt_user_connections_current{user="hello"} 461
telemt_user_octets_from_client{user="hello"} 10542008616 (9.82 GB)
telemt_user_octets_to_client{user="hello"} 231676055008 (215.77 GB)
telemt_user_unique_ips_current{user="hello"} 168
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 38732.6 (10h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 346773
telemt_connections_bad_total 2404
telemt_handshake_timeouts_total 17767
telemt_upstream_connect_attempt_total 15572
telemt_upstream_connect_success_total 12690
telemt_upstream_connect_fail_total 2882
telemt_upstream_connect_attempts_per_request{bucket="1"} 15572
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5512
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4938
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2031
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2882
telemt_me_keepalive_timeout_total 1715
telemt_me_reconnect_attempts_total 8599
telemt_me_reconnect_success_total 7783
telemt_me_reader_eof_total 8216
telemt_me_idle_close_by_peer_total 8214
telemt_me_route_drop_no_conn_total 173638
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 295948
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1776
telemt_desync_full_logged_total 508
telemt_desync_suppressed_total 1268
telemt_desync_frames_bucket_total{bucket="1_2"} 544
telemt_desync_frames_bucket_total{bucket="3_10"} 630
telemt_desync_frames_bucket_total{bucket="gt_10"} 602
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 7889
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 7762
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 106
telemt_user_connections_total{user="hello"} 298217
telemt_user_connections_current{user="hello"} 138
telemt_user_octets_from_client{user="hello"} 2855533434 (2.66 GB)
telemt_user_octets_to_client{user="hello"} 70874457164 (66.01 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 38732.5 (10h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 576357
telemt_connections_bad_total 4113
telemt_handshake_timeouts_total 34198
telemt_upstream_connect_attempt_total 10575
telemt_upstream_connect_success_total 10429
telemt_upstream_connect_fail_total 145
telemt_upstream_connect_attempts_per_request{bucket="1"} 10574
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5853
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4510
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 145
telemt_me_keepalive_timeout_total 513
telemt_me_reconnect_attempts_total 18459
telemt_me_reconnect_success_total 7397
telemt_me_reader_eof_total 8058
telemt_me_idle_close_by_peer_total 8058
telemt_me_route_drop_no_conn_total 197563
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 509488
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
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 7842
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 7386
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 445
telemt_user_connections_total{user="hello"} 510403
telemt_user_connections_current{user="hello"} 155
telemt_user_octets_from_client{user="hello"} 6902161905 (6.43 GB)
telemt_user_octets_to_client{user="hello"} 155474751433 (144.80 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 38732.8 (10h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 424999
telemt_connections_bad_total 36793
telemt_handshake_timeouts_total 40273
telemt_upstream_connect_attempt_total 11093
telemt_upstream_connect_success_total 11093
telemt_upstream_connect_attempts_per_request{bucket="1"} 11093
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6246
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4845
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 415
telemt_me_reconnect_attempts_total 10167
telemt_me_reconnect_success_total 9133
telemt_me_reader_eof_total 9652
telemt_me_idle_close_by_peer_total 9652
telemt_me_seq_mismatch_total 6
telemt_me_route_drop_no_conn_total 129726
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 334877
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 17
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 726
telemt_desync_full_logged_total 290
telemt_desync_suppressed_total 436
telemt_desync_frames_bucket_total{bucket="1_2"} 278
telemt_desync_frames_bucket_total{bucket="3_10"} 252
telemt_desync_frames_bucket_total{bucket="gt_10"} 196
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 9250
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 9116
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 117
telemt_user_connections_total{user="hello"} 334553
telemt_user_connections_current{user="hello"} 172
telemt_user_octets_from_client{user="hello"} 4226885508 (3.94 GB)
telemt_user_octets_to_client{user="hello"} 91450583888 (85.17 GB)
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 38732.5 (10h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 449234
telemt_connections_bad_total 4951
telemt_handshake_timeouts_total 2903
telemt_upstream_connect_attempt_total 11620
telemt_upstream_connect_success_total 11571
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 11620
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5994
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5464
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 111
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_keepalive_timeout_total 510
telemt_me_reconnect_attempts_total 13351
telemt_me_reconnect_success_total 9583
telemt_me_reader_eof_total 10079
telemt_me_idle_close_by_peer_total 10079
telemt_me_route_drop_no_conn_total 148764
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 412613
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2280
telemt_desync_full_logged_total 883
telemt_desync_suppressed_total 1397
telemt_desync_frames_bucket_total{bucket="1_2"} 841
telemt_desync_frames_bucket_total{bucket="3_10"} 972
telemt_desync_frames_bucket_total{bucket="gt_10"} 467
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 9824
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 9583
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 241
telemt_user_connections_total{user="hello"} 412327
telemt_user_connections_current{user="hello"} 221
telemt_user_octets_from_client{user="hello"} 8383799340 (7.81 GB)
telemt_user_octets_to_client{user="hello"} 147552202080 (137.42 GB)
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 29
```