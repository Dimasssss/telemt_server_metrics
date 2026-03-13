# Server Metrics 2026-03-13 01:58:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 72007.7 (20h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2055023
telemt_connections_bad_total 26146
telemt_handshake_timeouts_total 21954
telemt_upstream_connect_attempt_total 14237
telemt_upstream_connect_success_total 14157
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 14237
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7292
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6824
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_keepalive_timeout_total 1253
telemt_me_reconnect_attempts_total 19436
telemt_me_reconnect_success_total 10575
telemt_me_reader_eof_total 11427
telemt_me_idle_close_by_peer_total 11426
telemt_me_route_drop_no_conn_total 799944
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1909549
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8700
telemt_desync_full_logged_total 2264
telemt_desync_suppressed_total 6436
telemt_desync_frames_bucket_total{bucket="1_2"} 2292
telemt_desync_frames_bucket_total{bucket="3_10"} 3138
telemt_desync_frames_bucket_total{bucket="gt_10"} 3270
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 11002
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 10562
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 427
telemt_user_connections_total{user="hello"} 1909006
telemt_user_connections_current{user="hello"} 538
telemt_user_octets_from_client{user="hello"} 27884492764 (25.97 GB)
telemt_user_octets_to_client{user="hello"} 666732142536 (620.94 GB)
telemt_user_unique_ips_current{user="hello"} 207
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 101628.2 (28h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 845597
telemt_connections_bad_total 11791
telemt_handshake_timeouts_total 32053
telemt_upstream_connect_attempt_total 25850
telemt_upstream_connect_success_total 25821
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 25850
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13426
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12306
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3450
telemt_me_reconnect_attempts_total 19232
telemt_me_reconnect_success_total 19126
telemt_me_reader_eof_total 20369
telemt_me_idle_close_by_peer_total 20369
telemt_me_route_drop_no_conn_total 272078
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 766727
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3078
telemt_desync_full_logged_total 967
telemt_desync_suppressed_total 2111
telemt_desync_frames_bucket_total{bucket="1_2"} 1251
telemt_desync_frames_bucket_total{bucket="3_10"} 999
telemt_desync_frames_bucket_total{bucket="gt_10"} 828
telemt_pool_swap_total 103
telemt_me_writer_removed_unexpected_total 19313
telemt_me_writer_restored_same_endpoint_total 19117
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 187
telemt_user_connections_total{user="hello"} 768630
telemt_user_connections_current{user="hello"} 221
telemt_user_octets_from_client{user="hello"} 12297426976 (11.45 GB)
telemt_user_octets_to_client{user="hello"} 290604597415 (270.65 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 101628.2 (28h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1755346
telemt_connections_bad_total 9007
telemt_handshake_timeouts_total 117476
telemt_upstream_connect_attempt_total 23685
telemt_upstream_connect_success_total 23675
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 23685
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12487
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11095
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 88
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1595
telemt_me_reconnect_attempts_total 19533
telemt_me_reconnect_success_total 18270
telemt_me_reader_eof_total 19343
telemt_me_idle_close_by_peer_total 19342
telemt_me_route_drop_no_conn_total 573919
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1379772
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4997
telemt_desync_full_logged_total 1533
telemt_desync_suppressed_total 3464
telemt_desync_frames_bucket_total{bucket="1_2"} 798
telemt_desync_frames_bucket_total{bucket="3_10"} 1807
telemt_desync_frames_bucket_total{bucket="gt_10"} 2392
telemt_pool_swap_total 94
telemt_me_writer_removed_unexpected_total 18443
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 18229
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 173
telemt_user_connections_total{user="hello"} 1379368
telemt_user_connections_current{user="hello"} 302
telemt_user_octets_from_client{user="hello"} 20134947776 (18.75 GB)
telemt_user_octets_to_client{user="hello"} 499345414201 (465.05 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 125
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 101628.1 (28h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1098910
telemt_connections_bad_total 13109
telemt_handshake_timeouts_total 72867
telemt_upstream_connect_attempt_total 35506
telemt_upstream_connect_success_total 33234
telemt_upstream_connect_fail_total 2135
telemt_upstream_connect_attempts_per_request{bucket="1"} 35232
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20584
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12561
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2134
telemt_me_keepalive_timeout_total 11280
telemt_me_reconnect_attempts_total 30163
telemt_me_reconnect_success_total 22319
telemt_me_reader_eof_total 24098
telemt_me_idle_close_by_peer_total 24091
telemt_me_route_drop_no_conn_total 388961
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 942141
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1895
telemt_desync_full_logged_total 628
telemt_desync_suppressed_total 1267
telemt_desync_frames_bucket_total{bucket="1_2"} 522
telemt_desync_frames_bucket_total{bucket="3_10"} 743
telemt_desync_frames_bucket_total{bucket="gt_10"} 630
telemt_pool_swap_total 86
telemt_me_writer_removed_unexpected_total 22708
telemt_me_refill_failed_total 241
telemt_me_writer_restored_same_endpoint_total 22297
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 2298
telemt_me_writer_removed_unexpected_minus_restored_total 389
telemt_user_connections_total{user="hello"} 947325
telemt_user_connections_current{user="hello"} 249
telemt_user_octets_from_client{user="hello"} 14495713573 (13.50 GB)
telemt_user_octets_to_client{user="hello"} 371230585286 (345.74 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 101628.2 (28h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1212457
telemt_connections_bad_total 12597
telemt_handshake_timeouts_total 9452
telemt_upstream_connect_attempt_total 31696
telemt_upstream_connect_success_total 31307
telemt_upstream_connect_fail_total 389
telemt_upstream_connect_attempts_per_request{bucket="1"} 31696
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15993
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15140
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 161
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 389
telemt_me_keepalive_timeout_total 1872
telemt_me_reconnect_attempts_total 37462
telemt_me_reconnect_success_total 26254
telemt_me_reader_eof_total 27561
telemt_me_idle_close_by_peer_total 27561
telemt_me_seq_mismatch_total 37
telemt_me_route_drop_no_conn_total 454024
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1120541
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 41
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4182
telemt_desync_full_logged_total 1482
telemt_desync_suppressed_total 2700
telemt_desync_frames_bucket_total{bucket="1_2"} 1254
telemt_desync_frames_bucket_total{bucket="3_10"} 1384
telemt_desync_frames_bucket_total{bucket="gt_10"} 1544
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 26908
telemt_me_refill_failed_total 347
telemt_me_writer_restored_same_endpoint_total 26206
telemt_me_writer_restored_fallback_total 48
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 654
telemt_user_connections_total{user="hello"} 1120397
telemt_user_connections_current{user="hello"} 308
telemt_user_octets_from_client{user="hello"} 13774749216 (12.83 GB)
telemt_user_octets_to_client{user="hello"} 385848354644 (359.35 GB)
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 34
```