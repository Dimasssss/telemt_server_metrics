# Server Metrics 2026-03-13 14:09:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 115832.7 (32h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3526922
telemt_connections_bad_total 37397
telemt_handshake_timeouts_total 60241
telemt_upstream_connect_attempt_total 22671
telemt_upstream_connect_success_total 22545
telemt_upstream_connect_fail_total 126
telemt_upstream_connect_attempts_per_request{bucket="1"} 22671
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11633
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10853
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 126
telemt_me_keepalive_timeout_total 2149
telemt_me_reconnect_attempts_total 26874
telemt_me_reconnect_success_total 16789
telemt_me_reader_eof_total 18049
telemt_me_idle_close_by_peer_total 18048
telemt_me_route_drop_no_conn_total 1308771
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3238412
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13408
telemt_desync_full_logged_total 3508
telemt_desync_suppressed_total 9900
telemt_desync_frames_bucket_total{bucket="1_2"} 3411
telemt_desync_frames_bucket_total{bucket="3_10"} 5068
telemt_desync_frames_bucket_total{bucket="gt_10"} 4929
telemt_pool_swap_total 95
telemt_me_writer_removed_unexpected_total 17339
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 16776
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 550
telemt_user_connections_total{user="hello"} 3238290
telemt_user_connections_current{user="hello"} 1772
telemt_user_octets_from_client{user="hello"} 44628787672 (41.56 GB)
telemt_user_octets_to_client{user="hello"} 1030566913712 (959.79 GB)
telemt_user_unique_ips_current{user="hello"} 473
telemt_user_unique_ips_recent_window{user="hello"} 262
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 15496.4 (4h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 216944
telemt_connections_bad_total 12337
telemt_handshake_timeouts_total 5494
telemt_upstream_connect_attempt_total 3865
telemt_upstream_connect_success_total 3787
telemt_upstream_connect_fail_total 78
telemt_upstream_connect_attempts_per_request{bucket="1"} 3865
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1936
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1810
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 78
telemt_me_keepalive_timeout_total 74
telemt_me_reconnect_attempts_total 5043
telemt_me_reconnect_success_total 2947
telemt_me_reader_eof_total 3110
telemt_me_idle_close_by_peer_total 3110
telemt_me_route_drop_no_conn_total 79010
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 193470
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 738
telemt_desync_full_logged_total 177
telemt_desync_suppressed_total 561
telemt_desync_frames_bucket_total{bucket="1_2"} 137
telemt_desync_frames_bucket_total{bucket="3_10"} 374
telemt_desync_frames_bucket_total{bucket="gt_10"} 227
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 3041
telemt_me_refill_failed_total 63
telemt_me_writer_restored_same_endpoint_total 2940
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 193494
telemt_user_connections_current{user="hello"} 609
telemt_user_octets_from_client{user="hello"} 1975340864 (1.84 GB)
telemt_user_octets_to_client{user="hello"} 55334712760 (51.53 GB)
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 114
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 145452.9 (40h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2644321
telemt_connections_bad_total 27068
telemt_handshake_timeouts_total 177276
telemt_upstream_connect_attempt_total 32839
telemt_upstream_connect_success_total 32829
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 32839
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17081
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15622
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 121
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3237
telemt_me_reconnect_attempts_total 27799
telemt_me_reconnect_success_total 25253
telemt_me_reader_eof_total 26777
telemt_me_idle_close_by_peer_total 26776
telemt_me_route_drop_no_conn_total 888758
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2158498
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7645
telemt_desync_full_logged_total 2494
telemt_desync_suppressed_total 5151
telemt_desync_frames_bucket_total{bucket="1_2"} 1199
telemt_desync_frames_bucket_total{bucket="3_10"} 2778
telemt_desync_frames_bucket_total{bucket="gt_10"} 3668
telemt_pool_swap_total 136
telemt_me_writer_removed_unexpected_total 25549
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 25212
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 296
telemt_user_connections_total{user="hello"} 2157901
telemt_user_connections_current{user="hello"} 1104
telemt_user_octets_from_client{user="hello"} 36034520804 (33.56 GB)
telemt_user_octets_to_client{user="hello"} 767010603021 (714.33 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 307
telemt_user_unique_ips_recent_window{user="hello"} 190
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 145453.4 (40h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1686852
telemt_connections_bad_total 18058
telemt_handshake_timeouts_total 122301
telemt_upstream_connect_attempt_total 46261
telemt_upstream_connect_success_total 43939
telemt_upstream_connect_fail_total 2185
telemt_upstream_connect_attempts_per_request{bucket="1"} 45987
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26470
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17378
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2184
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11843
telemt_me_reconnect_attempts_total 39816
telemt_me_reconnect_success_total 30849
telemt_me_reader_eof_total 33167
telemt_me_idle_close_by_peer_total 33160
telemt_me_route_drop_no_conn_total 601528
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1410083
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2814
telemt_desync_full_logged_total 914
telemt_desync_suppressed_total 1900
telemt_desync_frames_bucket_total{bucket="1_2"} 750
telemt_desync_frames_bucket_total{bucket="3_10"} 1171
telemt_desync_frames_bucket_total{bucket="gt_10"} 893
telemt_pool_swap_total 127
telemt_me_writer_removed_unexpected_total 31359
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 30825
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 510
telemt_user_connections_total{user="hello"} 1414798
telemt_user_connections_current{user="hello"} 681
telemt_user_octets_from_client{user="hello"} 21833162085 (20.33 GB)
telemt_user_octets_to_client{user="hello"} 547002990834 (509.44 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 203
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 14889.2 (4h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 234602
telemt_connections_bad_total 3868
telemt_handshake_timeouts_total 2196
telemt_upstream_connect_attempt_total 3087
telemt_upstream_connect_success_total 2983
telemt_upstream_connect_fail_total 104
telemt_upstream_connect_attempts_per_request{bucket="1"} 3087
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1429
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1550
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 104
telemt_me_keepalive_timeout_total 54
telemt_me_reconnect_attempts_total 10276
telemt_me_reconnect_success_total 2200
telemt_me_reader_eof_total 2479
telemt_me_idle_close_by_peer_total 2479
telemt_me_route_drop_no_conn_total 91840
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 219233
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 759
telemt_desync_full_logged_total 241
telemt_desync_suppressed_total 518
telemt_desync_frames_bucket_total{bucket="1_2"} 293
telemt_desync_frames_bucket_total{bucket="3_10"} 297
telemt_desync_frames_bucket_total{bucket="gt_10"} 169
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 2456
telemt_me_refill_failed_total 251
telemt_me_writer_restored_same_endpoint_total 2196
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 256
telemt_user_connections_total{user="hello"} 219215
telemt_user_connections_current{user="hello"} 778
telemt_user_octets_from_client{user="hello"} 2386033420 (2.22 GB)
telemt_user_octets_to_client{user="hello"} 69611393224 (64.83 GB)
telemt_user_unique_ips_current{user="hello"} 193
telemt_user_unique_ips_recent_window{user="hello"} 103
```