# Server Metrics 2026-03-13 21:17:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 141540.8 (39h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4466575
telemt_connections_bad_total 38132
telemt_handshake_timeouts_total 106406
telemt_upstream_connect_attempt_total 29615
telemt_upstream_connect_success_total 29410
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 29615
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16158
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13109
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 143
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_timeout_total 6615
telemt_me_reconnect_attempts_total 30121
telemt_me_reconnect_success_total 20003
telemt_me_reader_eof_total 21462
telemt_me_idle_close_by_peer_total 21461
telemt_me_route_drop_no_conn_total 1684150
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4091507
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16306
telemt_desync_full_logged_total 4353
telemt_desync_suppressed_total 11953
telemt_desync_frames_bucket_total{bucket="1_2"} 4072
telemt_desync_frames_bucket_total{bucket="3_10"} 6228
telemt_desync_frames_bucket_total{bucket="gt_10"} 6006
telemt_pool_swap_total 120
telemt_me_writer_removed_unexpected_total 20605
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 19990
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 602
telemt_user_connections_total{user="hello"} 4093638
telemt_user_connections_current{user="hello"} 1017
telemt_user_octets_from_client{user="hello"} 60285854468 (56.15 GB)
telemt_user_octets_to_client{user="hello"} 1293783708957 (1.18 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 291
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 41204.5 (11h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 567289
telemt_connections_bad_total 41499
telemt_handshake_timeouts_total 12247
telemt_upstream_connect_attempt_total 11748
telemt_upstream_connect_success_total 11526
telemt_upstream_connect_fail_total 222
telemt_upstream_connect_attempts_per_request{bucket="1"} 11748
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6729
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4580
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 21
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 196
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 222
telemt_me_keepalive_timeout_total 1896
telemt_me_reconnect_attempts_total 10858
telemt_me_reconnect_success_total 7434
telemt_me_reader_eof_total 7862
telemt_me_idle_close_by_peer_total 7861
telemt_me_route_drop_no_conn_total 208552
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 492473
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1636
telemt_desync_full_logged_total 440
telemt_desync_suppressed_total 1196
telemt_desync_frames_bucket_total{bucket="1_2"} 345
telemt_desync_frames_bucket_total{bucket="3_10"} 709
telemt_desync_frames_bucket_total{bucket="gt_10"} 582
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 7647
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 7426
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 213
telemt_user_connections_total{user="hello"} 494400
telemt_user_connections_current{user="hello"} 319
telemt_user_octets_from_client{user="hello"} 5306773969 (4.94 GB)
telemt_user_octets_to_client{user="hello"} 161102219436 (150.04 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 171161.2 (47h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3251012
telemt_connections_bad_total 30853
telemt_handshake_timeouts_total 218344
telemt_upstream_connect_attempt_total 38048
telemt_upstream_connect_success_total 38027
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 38048
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19819
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17988
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 213
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10258
telemt_me_reconnect_attempts_total 34112
telemt_me_reconnect_success_total 29164
telemt_me_reader_eof_total 30952
telemt_me_idle_close_by_peer_total 30951
telemt_me_route_drop_no_conn_total 1113026
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2695650
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8886
telemt_desync_full_logged_total 2984
telemt_desync_suppressed_total 5902
telemt_desync_frames_bucket_total{bucket="1_2"} 1466
telemt_desync_frames_bucket_total{bucket="3_10"} 3235
telemt_desync_frames_bucket_total{bucket="gt_10"} 4185
telemt_pool_swap_total 158
telemt_me_writer_removed_unexpected_total 29593
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 29123
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 429
telemt_user_connections_total{user="hello"} 2694925
telemt_user_connections_current{user="hello"} 674
telemt_user_octets_from_client{user="hello"} 44232391064 (41.19 GB)
telemt_user_octets_to_client{user="hello"} 950445026357 (885.17 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 199
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 171161.5 (47h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2114155
telemt_connections_bad_total 22798
telemt_handshake_timeouts_total 206396
telemt_upstream_connect_attempt_total 53221
telemt_upstream_connect_success_total 50777
telemt_upstream_connect_fail_total 2307
telemt_upstream_connect_attempts_per_request{bucket="1"} 52947
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30452
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20161
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 164
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2306
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20222
telemt_me_reconnect_attempts_total 44224
telemt_me_reconnect_success_total 35213
telemt_me_reader_eof_total 37787
telemt_me_idle_close_by_peer_total 37780
telemt_me_route_drop_no_conn_total 745467
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1737954
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3758
telemt_desync_full_logged_total 1200
telemt_desync_suppressed_total 2558
telemt_desync_frames_bucket_total{bucket="1_2"} 993
telemt_desync_frames_bucket_total{bucket="3_10"} 1560
telemt_desync_frames_bucket_total{bucket="gt_10"} 1205
telemt_pool_swap_total 150
telemt_me_writer_removed_unexpected_total 35797
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 35189
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 584
telemt_user_connections_total{user="hello"} 1743825
telemt_user_connections_current{user="hello"} 396
telemt_user_octets_from_client{user="hello"} 26990264691 (25.14 GB)
telemt_user_octets_to_client{user="hello"} 653381360470 (608.51 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 40597.3 (11h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 605234
telemt_connections_bad_total 5838
telemt_handshake_timeouts_total 5638
telemt_upstream_connect_attempt_total 8898
telemt_upstream_connect_success_total 8600
telemt_upstream_connect_fail_total 298
telemt_upstream_connect_attempts_per_request{bucket="1"} 8898
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4156
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4424
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 298
telemt_me_keepalive_timeout_total 973
telemt_me_reconnect_attempts_total 31177
telemt_me_reconnect_success_total 6556
telemt_me_reader_eof_total 7454
telemt_me_idle_close_by_peer_total 7453
telemt_me_route_drop_no_conn_total 229660
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 567666
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1487
telemt_desync_full_logged_total 464
telemt_desync_suppressed_total 1023
telemt_desync_frames_bucket_total{bucket="1_2"} 448
telemt_desync_frames_bucket_total{bucket="3_10"} 593
telemt_desync_frames_bucket_total{bucket="gt_10"} 446
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 7384
telemt_me_refill_failed_total 767
telemt_me_writer_restored_same_endpoint_total 6552
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 828
telemt_user_connections_total{user="hello"} 567581
telemt_user_connections_current{user="hello"} 414
telemt_user_octets_from_client{user="hello"} 8451013256 (7.87 GB)
telemt_user_octets_to_client{user="hello"} 181410163476 (168.95 GB)
telemt_user_unique_ips_current{user="hello"} 128
telemt_user_unique_ips_recent_window{user="hello"} 41
```