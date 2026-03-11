# Server Metrics 2026-03-11 12:08:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 78059.7 (21h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1784724
telemt_connections_bad_total 25419
telemt_handshake_timeouts_total 46165
telemt_upstream_connect_attempt_total 16232
telemt_upstream_connect_success_total 16223
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 16232
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8183
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7970
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 69
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 837
telemt_me_reconnect_attempts_total 25109
telemt_me_reconnect_success_total 12286
telemt_me_reader_eof_total 13290
telemt_me_idle_close_by_peer_total 13290
telemt_me_route_drop_no_conn_total 655673
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1626537
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8522
telemt_desync_full_logged_total 2293
telemt_desync_suppressed_total 6229
telemt_desync_frames_bucket_total{bucket="1_2"} 2129
telemt_desync_frames_bucket_total{bucket="3_10"} 3265
telemt_desync_frames_bucket_total{bucket="gt_10"} 3128
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 12815
telemt_me_refill_failed_total 398
telemt_me_writer_restored_same_endpoint_total 12280
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 529
telemt_user_connections_total{user="hello"} 1625082
telemt_user_connections_current{user="hello"} 1587
telemt_user_octets_from_client{user="hello"} 21433658956 (19.96 GB)
telemt_user_octets_to_client{user="hello"} 461619917752 (429.92 GB)
telemt_user_unique_ips_current{user="hello"} 394
telemt_user_unique_ips_recent_window{user="hello"} 207
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 78116.4 (21h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 673591
telemt_connections_bad_total 12423
telemt_handshake_timeouts_total 43527
telemt_upstream_connect_attempt_total 25527
telemt_upstream_connect_success_total 22588
telemt_upstream_connect_fail_total 2939
telemt_upstream_connect_attempts_per_request{bucket="1"} 25527
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10370
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9975
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2939
telemt_me_keepalive_timeout_total 2197
telemt_me_reconnect_attempts_total 16590
telemt_me_reconnect_success_total 15739
telemt_me_reader_eof_total 16658
telemt_me_idle_close_by_peer_total 16656
telemt_me_route_drop_no_conn_total 270214
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 570220
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2596
telemt_desync_full_logged_total 816
telemt_desync_suppressed_total 1780
telemt_desync_frames_bucket_total{bucket="1_2"} 831
telemt_desync_frames_bucket_total{bucket="3_10"} 947
telemt_desync_frames_bucket_total{bucket="gt_10"} 818
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 15935
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 15717
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 196
telemt_user_connections_total{user="hello"} 572445
telemt_user_connections_current{user="hello"} 528
telemt_user_octets_from_client{user="hello"} 6084188022 (5.67 GB)
telemt_user_octets_to_client{user="hello"} 162530797520 (151.37 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 78116.3 (21h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1175229
telemt_connections_bad_total 7892
telemt_handshake_timeouts_total 110449
telemt_upstream_connect_attempt_total 20946
telemt_upstream_connect_success_total 20693
telemt_upstream_connect_fail_total 253
telemt_upstream_connect_attempts_per_request{bucket="1"} 20946
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11267
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9325
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 253
telemt_me_keepalive_timeout_total 842
telemt_me_reconnect_attempts_total 29335
telemt_me_reconnect_success_total 15704
telemt_me_reader_eof_total 16862
telemt_me_idle_close_by_peer_total 16862
telemt_me_route_drop_no_conn_total 393783
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1010980
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2707
telemt_desync_full_logged_total 806
telemt_desync_suppressed_total 1901
telemt_desync_frames_bucket_total{bucket="1_2"} 638
telemt_desync_frames_bucket_total{bucket="3_10"} 1017
telemt_desync_frames_bucket_total{bucket="gt_10"} 1052
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 16336
telemt_me_refill_failed_total 422
telemt_me_writer_restored_same_endpoint_total 15693
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 632
telemt_user_connections_total{user="hello"} 1011717
telemt_user_connections_current{user="hello"} 706
telemt_user_octets_from_client{user="hello"} 11750552305 (10.94 GB)
telemt_user_octets_to_client{user="hello"} 305169753813 (284.21 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 217
telemt_user_unique_ips_recent_window{user="hello"} 114
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 78116.7 (21h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 846577
telemt_connections_bad_total 73318
telemt_handshake_timeouts_total 76915
telemt_upstream_connect_attempt_total 21125
telemt_upstream_connect_success_total 21125
telemt_upstream_connect_attempts_per_request{bucket="1"} 21125
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11601
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9520
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 850
telemt_me_reconnect_attempts_total 18297
telemt_me_reconnect_success_total 17233
telemt_me_reader_eof_total 18287
telemt_me_idle_close_by_peer_total 18286
telemt_me_seq_mismatch_total 15
telemt_me_route_drop_no_conn_total 270249
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 672425
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 26
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1448
telemt_desync_full_logged_total 560
telemt_desync_suppressed_total 888
telemt_desync_frames_bucket_total{bucket="1_2"} 513
telemt_desync_frames_bucket_total{bucket="3_10"} 525
telemt_desync_frames_bucket_total{bucket="gt_10"} 410
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 17443
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 17207
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 210
telemt_user_connections_total{user="hello"} 671790
telemt_user_connections_current{user="hello"} 576
telemt_user_octets_from_client{user="hello"} 7655744280 (7.13 GB)
telemt_user_octets_to_client{user="hello"} 191309541460 (178.17 GB)
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 78116.5 (21h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 913382
telemt_connections_bad_total 6244
telemt_handshake_timeouts_total 8722
telemt_upstream_connect_attempt_total 21445
telemt_upstream_connect_success_total 21352
telemt_upstream_connect_fail_total 93
telemt_upstream_connect_attempts_per_request{bucket="1"} 21445
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10949
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10225
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 174
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 93
telemt_me_keepalive_timeout_total 907
telemt_me_reconnect_attempts_total 21400
telemt_me_reconnect_success_total 17339
telemt_me_reader_eof_total 18290
telemt_me_idle_close_by_peer_total 18290
telemt_me_route_drop_no_conn_total 320912
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 829608
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3412
telemt_desync_full_logged_total 1260
telemt_desync_suppressed_total 2152
telemt_desync_frames_bucket_total{bucket="1_2"} 1160
telemt_desync_frames_bucket_total{bucket="3_10"} 1330
telemt_desync_frames_bucket_total{bucket="gt_10"} 922
telemt_pool_swap_total 53
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 17686
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 17339
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 347
telemt_user_connections_total{user="hello"} 829364
telemt_user_connections_current{user="hello"} 818
telemt_user_octets_from_client{user="hello"} 12359884623 (11.51 GB)
telemt_user_octets_to_client{user="hello"} 300863174006 (280.20 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 199
telemt_user_unique_ips_recent_window{user="hello"} 102
```