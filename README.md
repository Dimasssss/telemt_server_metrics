# Server Metrics 2026-03-13 04:06:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 79657.3 (22h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2174598
telemt_connections_bad_total 28934
telemt_handshake_timeouts_total 23060
telemt_upstream_connect_attempt_total 15775
telemt_upstream_connect_success_total 15687
telemt_upstream_connect_fail_total 88
telemt_upstream_connect_attempts_per_request{bucket="1"} 15775
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8088
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7554
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 88
telemt_me_keepalive_timeout_total 1299
telemt_me_reconnect_attempts_total 20577
telemt_me_reconnect_success_total 11712
telemt_me_reader_eof_total 12646
telemt_me_idle_close_by_peer_total 12645
telemt_me_route_drop_no_conn_total 831997
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2000408
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8875
telemt_desync_full_logged_total 2304
telemt_desync_suppressed_total 6571
telemt_desync_frames_bucket_total{bucket="1_2"} 2337
telemt_desync_frames_bucket_total{bucket="3_10"} 3196
telemt_desync_frames_bucket_total{bucket="gt_10"} 3342
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 12152
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 11699
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 440
telemt_user_connections_total{user="hello"} 1999836
telemt_user_connections_current{user="hello"} 877
telemt_user_octets_from_client{user="hello"} 28937728200 (26.95 GB)
telemt_user_octets_to_client{user="hello"} 688166749248 (640.91 GB)
telemt_user_unique_ips_current{user="hello"} 290
telemt_user_unique_ips_recent_window{user="hello"} 145
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 109277.8 (30h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 884851
telemt_connections_bad_total 11848
telemt_handshake_timeouts_total 39248
telemt_upstream_connect_attempt_total 27831
telemt_upstream_connect_success_total 27802
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 27831
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14389
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13323
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3472
telemt_me_reconnect_attempts_total 20823
telemt_me_reconnect_success_total 20711
telemt_me_reader_eof_total 22074
telemt_me_idle_close_by_peer_total 22074
telemt_me_route_drop_no_conn_total 282896
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 797550
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3153
telemt_desync_full_logged_total 991
telemt_desync_suppressed_total 2162
telemt_desync_frames_bucket_total{bucket="1_2"} 1270
telemt_desync_frames_bucket_total{bucket="3_10"} 1027
telemt_desync_frames_bucket_total{bucket="gt_10"} 856
telemt_pool_swap_total 112
telemt_me_writer_removed_unexpected_total 20913
telemt_me_writer_restored_same_endpoint_total 20702
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 202
telemt_user_connections_total{user="hello"} 799453
telemt_user_connections_current{user="hello"} 353
telemt_user_octets_from_client{user="hello"} 12736974400 (11.86 GB)
telemt_user_octets_to_client{user="hello"} 309260505483 (288.02 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 109277.6 (30h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1829068
telemt_connections_bad_total 14271
telemt_handshake_timeouts_total 120543
telemt_upstream_connect_attempt_total 25498
telemt_upstream_connect_success_total 25488
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 25498
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13381
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12008
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 94
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1627
telemt_me_reconnect_attempts_total 20955
telemt_me_reconnect_success_total 19688
telemt_me_reader_eof_total 20852
telemt_me_idle_close_by_peer_total 20851
telemt_me_route_drop_no_conn_total 592613
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1443545
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5106
telemt_desync_full_logged_total 1558
telemt_desync_suppressed_total 3548
telemt_desync_frames_bucket_total{bucket="1_2"} 817
telemt_desync_frames_bucket_total{bucket="3_10"} 1845
telemt_desync_frames_bucket_total{bucket="gt_10"} 2444
telemt_pool_swap_total 102
telemt_me_writer_removed_unexpected_total 19874
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 19647
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 186
telemt_user_connections_total{user="hello"} 1443156
telemt_user_connections_current{user="hello"} 508
telemt_user_octets_from_client{user="hello"} 24938139856 (23.23 GB)
telemt_user_octets_to_client{user="hello"} 515853326521 (480.43 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 177
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 109278.0 (30h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1135622
telemt_connections_bad_total 13172
telemt_handshake_timeouts_total 74585
telemt_upstream_connect_attempt_total 37845
telemt_upstream_connect_success_total 35563
telemt_upstream_connect_fail_total 2145
telemt_upstream_connect_attempts_per_request{bucket="1"} 37571
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21968
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13504
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2144
telemt_me_keepalive_timeout_total 11381
telemt_me_reconnect_attempts_total 33180
telemt_me_reconnect_success_total 24249
telemt_me_reader_eof_total 26175
telemt_me_idle_close_by_peer_total 26168
telemt_me_route_drop_no_conn_total 403309
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 975689
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1937
telemt_desync_full_logged_total 640
telemt_desync_suppressed_total 1297
telemt_desync_frames_bucket_total{bucket="1_2"} 539
telemt_desync_frames_bucket_total{bucket="3_10"} 757
telemt_desync_frames_bucket_total{bucket="gt_10"} 641
telemt_pool_swap_total 94
telemt_me_writer_removed_unexpected_total 24686
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 24225
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 437
telemt_user_connections_total{user="hello"} 980867
telemt_user_connections_current{user="hello"} 334
telemt_user_octets_from_client{user="hello"} 15063122921 (14.03 GB)
telemt_user_octets_to_client{user="hello"} 386350456062 (359.82 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 113
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 109277.7 (30h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1260455
telemt_connections_bad_total 12877
telemt_handshake_timeouts_total 10123
telemt_upstream_connect_attempt_total 34521
telemt_upstream_connect_success_total 34098
telemt_upstream_connect_fail_total 423
telemt_upstream_connect_attempts_per_request{bucket="1"} 34521
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17451
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16459
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 173
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 423
telemt_me_keepalive_timeout_total 1920
telemt_me_reconnect_attempts_total 42386
telemt_me_reconnect_success_total 28654
telemt_me_reader_eof_total 30123
telemt_me_idle_close_by_peer_total 30123
telemt_me_seq_mismatch_total 38
telemt_me_route_drop_no_conn_total 468607
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1165573
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 42
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4289
telemt_desync_full_logged_total 1535
telemt_desync_suppressed_total 2754
telemt_desync_frames_bucket_total{bucket="1_2"} 1298
telemt_desync_frames_bucket_total{bucket="3_10"} 1403
telemt_desync_frames_bucket_total{bucket="gt_10"} 1588
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 29412
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 28604
telemt_me_writer_restored_fallback_total 50
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 758
telemt_user_connections_total{user="hello"} 1165427
telemt_user_connections_current{user="hello"} 471
telemt_user_octets_from_client{user="hello"} 14298639532 (13.32 GB)
telemt_user_octets_to_client{user="hello"} 400081942612 (372.61 GB)
telemt_user_unique_ips_current{user="hello"} 130
telemt_user_unique_ips_recent_window{user="hello"} 59
```