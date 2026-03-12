# Server Metrics 2026-03-12 17:02:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 39855.0 (11h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1439667
telemt_connections_bad_total 20276
telemt_handshake_timeouts_total 13663
telemt_upstream_connect_attempt_total 7994
telemt_upstream_connect_success_total 7948
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 7994
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4174
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3750
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_timeout_total 481
telemt_me_reconnect_attempts_total 13564
telemt_me_reconnect_success_total 5905
telemt_me_reader_eof_total 6379
telemt_me_idle_close_by_peer_total 6378
telemt_me_route_drop_no_conn_total 531299
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1349334
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6836
telemt_desync_full_logged_total 1722
telemt_desync_suppressed_total 5114
telemt_desync_frames_bucket_total{bucket="1_2"} 1772
telemt_desync_frames_bucket_total{bucket="3_10"} 2471
telemt_desync_frames_bucket_total{bucket="gt_10"} 2593
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 6221
telemt_me_refill_failed_total 238
telemt_me_writer_restored_same_endpoint_total 5892
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 316
telemt_user_connections_total{user="hello"} 1349004
telemt_user_connections_current{user="hello"} 1967
telemt_user_octets_from_client{user="hello"} 20419758816 (19.02 GB)
telemt_user_octets_to_client{user="hello"} 402528529868 (374.88 GB)
telemt_user_unique_ips_current{user="hello"} 482
telemt_user_unique_ips_recent_window{user="hello"} 215
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 69475.3 (19h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 629671
telemt_connections_bad_total 8366
telemt_handshake_timeouts_total 28824
telemt_upstream_connect_attempt_total 16610
telemt_upstream_connect_success_total 16603
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 16610
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8286
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8299
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1318
telemt_me_reconnect_attempts_total 13005
telemt_me_reconnect_success_total 12930
telemt_me_reader_eof_total 13748
telemt_me_idle_close_by_peer_total 13748
telemt_me_route_drop_no_conn_total 193562
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 564807
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2352
telemt_desync_full_logged_total 728
telemt_desync_suppressed_total 1624
telemt_desync_frames_bucket_total{bucket="1_2"} 1007
telemt_desync_frames_bucket_total{bucket="3_10"} 762
telemt_desync_frames_bucket_total{bucket="gt_10"} 583
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 13060
telemt_me_writer_restored_same_endpoint_total 12921
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 130
telemt_user_connections_total{user="hello"} 565335
telemt_user_connections_current{user="hello"} 689
telemt_user_octets_from_client{user="hello"} 8699935171 (8.10 GB)
telemt_user_octets_to_client{user="hello"} 204745192194 (190.68 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 179
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 69475.3 (19h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1318696
telemt_connections_bad_total 6576
telemt_handshake_timeouts_total 95108
telemt_upstream_connect_attempt_total 16595
telemt_upstream_connect_success_total 16590
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 16595
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8953
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7568
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1111
telemt_me_reconnect_attempts_total 13969
telemt_me_reconnect_success_total 12734
telemt_me_reader_eof_total 13425
telemt_me_idle_close_by_peer_total 13424
telemt_me_route_drop_no_conn_total 378994
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 989106
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4241
telemt_desync_full_logged_total 1309
telemt_desync_suppressed_total 2932
telemt_desync_frames_bucket_total{bucket="1_2"} 657
telemt_desync_frames_bucket_total{bucket="3_10"} 1537
telemt_desync_frames_bucket_total{bucket="gt_10"} 2047
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 12834
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 12693
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 100
telemt_user_connections_total{user="hello"} 989219
telemt_user_connections_current{user="hello"} 1177
telemt_user_octets_from_client{user="hello"} 14896223212 (13.87 GB)
telemt_user_octets_to_client{user="hello"} 330352429157 (307.66 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 289
telemt_user_unique_ips_recent_window{user="hello"} 146
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 69475.8 (19h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 793432
telemt_connections_bad_total 8094
telemt_handshake_timeouts_total 61881
telemt_upstream_connect_attempt_total 18185
telemt_upstream_connect_success_total 18114
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 18185
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10248
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7853
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 1546
telemt_me_reconnect_attempts_total 19868
telemt_me_reconnect_success_total 14615
telemt_me_reader_eof_total 15571
telemt_me_idle_close_by_peer_total 15571
telemt_me_route_drop_no_conn_total 274979
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 687057
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1466
telemt_desync_full_logged_total 496
telemt_desync_suppressed_total 970
telemt_desync_frames_bucket_total{bucket="1_2"} 403
telemt_desync_frames_bucket_total{bucket="3_10"} 584
telemt_desync_frames_bucket_total{bucket="gt_10"} 479
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 14891
telemt_me_refill_failed_total 162
telemt_me_writer_restored_same_endpoint_total 14594
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 276
telemt_user_connections_total{user="hello"} 686484
telemt_user_connections_current{user="hello"} 711
telemt_user_octets_from_client{user="hello"} 8466827816 (7.89 GB)
telemt_user_octets_to_client{user="hello"} 271065796376 (252.45 GB)
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 115
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 69475.5 (19h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 896117
telemt_connections_bad_total 11391
telemt_handshake_timeouts_total 7308
telemt_upstream_connect_attempt_total 22065
telemt_upstream_connect_success_total 21799
telemt_upstream_connect_fail_total 266
telemt_upstream_connect_attempts_per_request{bucket="1"} 22065
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11169
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10512
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 110
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 266
telemt_me_keepalive_timeout_total 1264
telemt_me_reconnect_attempts_total 25547
telemt_me_reconnect_success_total 18302
telemt_me_reader_eof_total 19131
telemt_me_idle_close_by_peer_total 19131
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 323374
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 822967
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3247
telemt_desync_full_logged_total 1107
telemt_desync_suppressed_total 2140
telemt_desync_frames_bucket_total{bucket="1_2"} 882
telemt_desync_frames_bucket_total{bucket="3_10"} 1105
telemt_desync_frames_bucket_total{bucket="gt_10"} 1260
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 18725
telemt_me_refill_failed_total 224
telemt_me_writer_restored_same_endpoint_total 18258
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 423
telemt_user_connections_total{user="hello"} 822852
telemt_user_connections_current{user="hello"} 935
telemt_user_octets_from_client{user="hello"} 10114157016 (9.42 GB)
telemt_user_octets_to_client{user="hello"} 242733715968 (226.06 GB)
telemt_user_unique_ips_current{user="hello"} 238
telemt_user_unique_ips_recent_window{user="hello"} 112
```