# Server Metrics 2026-03-14 06:24:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 174361.6 (48h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4909776
telemt_connections_bad_total 40034
telemt_handshake_timeouts_total 112734
telemt_upstream_connect_attempt_total 36625
telemt_upstream_connect_success_total 36387
telemt_upstream_connect_fail_total 238
telemt_upstream_connect_attempts_per_request{bucket="1"} 36625
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19780
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16459
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 148
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 238
telemt_me_keepalive_timeout_total 7319
telemt_me_reconnect_attempts_total 35537
telemt_me_reconnect_success_total 25388
telemt_me_reader_eof_total 27248
telemt_me_idle_close_by_peer_total 27247
telemt_me_route_drop_no_conn_total 1860344
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4506818
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 17294
telemt_desync_full_logged_total 4677
telemt_desync_suppressed_total 12617
telemt_desync_frames_bucket_total{bucket="1_2"} 4314
telemt_desync_frames_bucket_total{bucket="3_10"} 6602
telemt_desync_frames_bucket_total{bucket="gt_10"} 6378
telemt_pool_swap_total 153
telemt_me_writer_removed_unexpected_total 26070
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 25375
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 682
telemt_user_connections_total{user="hello"} 4508329
telemt_user_connections_current{user="hello"} 1250
telemt_user_octets_from_client{user="hello"} 65803049744 (61.28 GB)
telemt_user_octets_to_client{user="hello"} 1421607626121 (1.29 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 389
telemt_user_unique_ips_recent_window{user="hello"} 193
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 74025.6 (20h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 806018
telemt_connections_bad_total 53806
telemt_handshake_timeouts_total 14743
telemt_upstream_connect_attempt_total 20126
telemt_upstream_connect_success_total 19856
telemt_upstream_connect_fail_total 270
telemt_upstream_connect_attempts_per_request{bucket="1"} 20126
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10930
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8663
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 230
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 270
telemt_me_keepalive_timeout_total 2139
telemt_me_reconnect_attempts_total 17587
telemt_me_reconnect_success_total 14125
telemt_me_reader_eof_total 15010
telemt_me_idle_close_by_peer_total 15009
telemt_me_route_drop_no_conn_total 264040
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 639068
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1870
telemt_desync_full_logged_total 564
telemt_desync_suppressed_total 1306
telemt_desync_frames_bucket_total{bucket="1_2"} 386
telemt_desync_frames_bucket_total{bucket="3_10"} 842
telemt_desync_frames_bucket_total{bucket="gt_10"} 642
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 14430
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 14117
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 305
telemt_user_connections_total{user="hello"} 640985
telemt_user_connections_current{user="hello"} 437
telemt_user_octets_from_client{user="hello"} 6733746537 (6.27 GB)
telemt_user_octets_to_client{user="hello"} 214406678668 (199.68 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 203982.2 (56h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3525898
telemt_connections_bad_total 38567
telemt_handshake_timeouts_total 232029
telemt_upstream_connect_attempt_total 46144
telemt_upstream_connect_success_total 46123
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 46144
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24325
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21550
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 241
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10658
telemt_me_reconnect_attempts_total 40643
telemt_me_reconnect_success_total 35670
telemt_me_reader_eof_total 37889
telemt_me_idle_close_by_peer_total 37888
telemt_me_route_drop_no_conn_total 1207109
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2941239
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9702
telemt_desync_full_logged_total 3255
telemt_desync_suppressed_total 6447
telemt_desync_frames_bucket_total{bucket="1_2"} 1692
telemt_desync_frames_bucket_total{bucket="3_10"} 3503
telemt_desync_frames_bucket_total{bucket="gt_10"} 4507
telemt_pool_swap_total 193
telemt_me_writer_removed_unexpected_total 36164
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 35629
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 494
telemt_user_connections_total{user="hello"} 2940399
telemt_user_connections_current{user="hello"} 701
telemt_user_octets_from_client{user="hello"} 48607516540 (45.27 GB)
telemt_user_octets_to_client{user="hello"} 1052160297949 (979.90 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 232
telemt_user_unique_ips_recent_window{user="hello"} 110
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 203985.0 (56h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2356827
telemt_connections_bad_total 23198
telemt_handshake_timeouts_total 276462
telemt_upstream_connect_attempt_total 63619
telemt_upstream_connect_success_total 61131
telemt_upstream_connect_fail_total 2351
telemt_upstream_connect_attempts_per_request{bucket="1"} 63345
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36504
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24461
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2350
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20503
telemt_me_reconnect_attempts_total 53012
telemt_me_reconnect_success_total 43967
telemt_me_reader_eof_total 47142
telemt_me_idle_close_by_peer_total 47135
telemt_me_route_drop_no_conn_total 795292
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1861021
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3896
telemt_desync_full_logged_total 1261
telemt_desync_suppressed_total 2635
telemt_desync_frames_bucket_total{bucket="1_2"} 1053
telemt_desync_frames_bucket_total{bucket="3_10"} 1617
telemt_desync_frames_bucket_total{bucket="gt_10"} 1226
telemt_pool_swap_total 181
telemt_me_writer_removed_unexpected_total 44630
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 43943
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 663
telemt_user_connections_total{user="hello"} 1867054
telemt_user_connections_current{user="hello"} 320
telemt_user_octets_from_client{user="hello"} 28191904959 (26.26 GB)
telemt_user_octets_to_client{user="hello"} 686855987398 (639.68 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 114
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 73418.6 (20h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 779801
telemt_connections_bad_total 8072
telemt_handshake_timeouts_total 9131
telemt_upstream_connect_attempt_total 18750
telemt_upstream_connect_success_total 18247
telemt_upstream_connect_fail_total 503
telemt_upstream_connect_attempts_per_request{bucket="1"} 18750
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8668
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9553
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 503
telemt_me_keepalive_timeout_total 1571
telemt_me_reconnect_attempts_total 59891
telemt_me_reconnect_success_total 14586
telemt_me_reader_eof_total 16357
telemt_me_idle_close_by_peer_total 16356
telemt_me_route_drop_no_conn_total 300400
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 728392
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1772
telemt_desync_full_logged_total 568
telemt_desync_suppressed_total 1204
telemt_desync_frames_bucket_total{bucket="1_2"} 528
telemt_desync_frames_bucket_total{bucket="3_10"} 689
telemt_desync_frames_bucket_total{bucket="gt_10"} 555
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 16127
telemt_me_refill_failed_total 1411
telemt_me_writer_restored_same_endpoint_total 14581
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1541
telemt_user_connections_total{user="hello"} 728249
telemt_user_connections_current{user="hello"} 593
telemt_user_octets_from_client{user="hello"} 12921402876 (12.03 GB)
telemt_user_octets_to_client{user="hello"} 244928849144 (228.11 GB)
telemt_user_unique_ips_current{user="hello"} 176
telemt_user_unique_ips_recent_window{user="hello"} 78
```