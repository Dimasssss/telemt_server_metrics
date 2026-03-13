# Server Metrics 2026-03-13 19:00:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 133288.3 (37h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4260734
telemt_connections_bad_total 37748
telemt_handshake_timeouts_total 103582
telemt_upstream_connect_attempt_total 28038
telemt_upstream_connect_success_total 27848
telemt_upstream_connect_fail_total 190
telemt_upstream_connect_attempts_per_request{bucket="1"} 28038
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15409
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12310
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 129
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 190
telemt_me_keepalive_timeout_total 6507
telemt_me_reconnect_attempts_total 28959
telemt_me_reconnect_success_total 18844
telemt_me_reader_eof_total 20229
telemt_me_idle_close_by_peer_total 20228
telemt_me_route_drop_no_conn_total 1597631
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3894943
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 15311
telemt_desync_full_logged_total 4076
telemt_desync_suppressed_total 11235
telemt_desync_frames_bucket_total{bucket="1_2"} 3805
telemt_desync_frames_bucket_total{bucket="3_10"} 5829
telemt_desync_frames_bucket_total{bucket="gt_10"} 5677
telemt_pool_swap_total 112
telemt_me_writer_removed_unexpected_total 19429
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 18831
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 585
telemt_user_connections_total{user="hello"} 3897113
telemt_user_connections_current{user="hello"} 1611
telemt_user_octets_from_client{user="hello"} 55042515024 (51.26 GB)
telemt_user_octets_to_client{user="hello"} 1222498496741 (1.11 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 415
telemt_user_unique_ips_recent_window{user="hello"} 194
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 32952.0 (9h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 482788
telemt_connections_bad_total 37688
telemt_handshake_timeouts_total 10913
telemt_upstream_connect_attempt_total 9838
telemt_upstream_connect_success_total 9627
telemt_upstream_connect_fail_total 211
telemt_upstream_connect_attempts_per_request{bucket="1"} 9838
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5694
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3727
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 20
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 186
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 211
telemt_me_keepalive_timeout_total 1863
telemt_me_reconnect_attempts_total 9346
telemt_me_reconnect_success_total 5935
telemt_me_reader_eof_total 6274
telemt_me_idle_close_by_peer_total 6273
telemt_me_route_drop_no_conn_total 181489
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 419723
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1459
telemt_desync_full_logged_total 390
telemt_desync_suppressed_total 1069
telemt_desync_frames_bucket_total{bucket="1_2"} 296
telemt_desync_frames_bucket_total{bucket="3_10"} 660
telemt_desync_frames_bucket_total{bucket="gt_10"} 503
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 6124
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 5927
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 189
telemt_user_connections_total{user="hello"} 421652
telemt_user_connections_current{user="hello"} 471
telemt_user_octets_from_client{user="hello"} 4468222117 (4.16 GB)
telemt_user_octets_to_client{user="hello"} 132637894588 (123.53 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 171
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 162908.9 (45h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3113087
telemt_connections_bad_total 28942
telemt_handshake_timeouts_total 208341
telemt_upstream_connect_attempt_total 36163
telemt_upstream_connect_success_total 36148
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 36163
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18695
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17316
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 132
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 10157
telemt_me_reconnect_attempts_total 30294
telemt_me_reconnect_success_total 27731
telemt_me_reader_eof_total 29399
telemt_me_idle_close_by_peer_total 29398
telemt_me_route_drop_no_conn_total 1063906
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2573832
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8665
telemt_desync_full_logged_total 2867
telemt_desync_suppressed_total 5798
telemt_desync_frames_bucket_total{bucket="1_2"} 1414
telemt_desync_frames_bucket_total{bucket="3_10"} 3174
telemt_desync_frames_bucket_total{bucket="gt_10"} 4077
telemt_pool_swap_total 153
telemt_me_writer_removed_unexpected_total 28059
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 27690
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 328
telemt_user_connections_total{user="hello"} 2573127
telemt_user_connections_current{user="hello"} 808
telemt_user_octets_from_client{user="hello"} 42311606400 (39.41 GB)
telemt_user_octets_to_client{user="hello"} 904255875421 (842.15 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 251
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 162909.6 (45h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2002559
telemt_connections_bad_total 21210
telemt_handshake_timeouts_total 183215
telemt_upstream_connect_attempt_total 51368
telemt_upstream_connect_success_total 48935
telemt_upstream_connect_fail_total 2296
telemt_upstream_connect_attempts_per_request{bucket="1"} 51094
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29574
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19197
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 164
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2295
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20167
telemt_me_reconnect_attempts_total 42817
telemt_me_reconnect_success_total 33812
telemt_me_reader_eof_total 36305
telemt_me_idle_close_by_peer_total 36298
telemt_me_route_drop_no_conn_total 712608
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1653036
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3424
telemt_desync_full_logged_total 1106
telemt_desync_suppressed_total 2318
telemt_desync_frames_bucket_total{bucket="1_2"} 925
telemt_desync_frames_bucket_total{bucket="3_10"} 1404
telemt_desync_frames_bucket_total{bucket="gt_10"} 1095
telemt_pool_swap_total 142
telemt_me_writer_removed_unexpected_total 34372
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 33788
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 560
telemt_user_connections_total{user="hello"} 1658910
telemt_user_connections_current{user="hello"} 612
telemt_user_octets_from_client{user="hello"} 25440311055 (23.69 GB)
telemt_user_octets_to_client{user="hello"} 628711312366 (585.53 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 159
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 32344.5 (8h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 523397
telemt_connections_bad_total 5430
telemt_handshake_timeouts_total 5236
telemt_upstream_connect_attempt_total 7020
telemt_upstream_connect_success_total 6788
telemt_upstream_connect_fail_total 232
telemt_upstream_connect_attempts_per_request{bucket="1"} 7020
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3192
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3577
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 232
telemt_me_keepalive_timeout_total 954
telemt_me_reconnect_attempts_total 24723
telemt_me_reconnect_success_total 5165
telemt_me_reader_eof_total 5866
telemt_me_idle_close_by_peer_total 5865
telemt_me_route_drop_no_conn_total 198437
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 489933
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1408
telemt_desync_full_logged_total 447
telemt_desync_suppressed_total 961
telemt_desync_frames_bucket_total{bucket="1_2"} 435
telemt_desync_frames_bucket_total{bucket="3_10"} 555
telemt_desync_frames_bucket_total{bucket="gt_10"} 418
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 5818
telemt_me_refill_failed_total 609
telemt_me_writer_restored_same_endpoint_total 5161
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 653
telemt_user_connections_total{user="hello"} 489896
telemt_user_connections_current{user="hello"} 708
telemt_user_octets_from_client{user="hello"} 5660203032 (5.27 GB)
telemt_user_octets_to_client{user="hello"} 157309382908 (146.51 GB)
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 82
```