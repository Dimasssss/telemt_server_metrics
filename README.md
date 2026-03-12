# Server Metrics 2026-03-12 19:56:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 50277.6 (13h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1753553
telemt_connections_bad_total 20545
telemt_handshake_timeouts_total 18374
telemt_upstream_connect_attempt_total 9818
telemt_upstream_connect_success_total 9763
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 9818
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5084
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4644
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_keepalive_timeout_total 576
telemt_me_reconnect_attempts_total 16076
telemt_me_reconnect_success_total 7229
telemt_me_reader_eof_total 7825
telemt_me_idle_close_by_peer_total 7824
telemt_me_route_drop_no_conn_total 691233
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1637573
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8138
telemt_desync_full_logged_total 2093
telemt_desync_suppressed_total 6045
telemt_desync_frames_bucket_total{bucket="1_2"} 2127
telemt_desync_frames_bucket_total{bucket="3_10"} 2933
telemt_desync_frames_bucket_total{bucket="gt_10"} 3078
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 7609
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 7216
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 380
telemt_user_connections_total{user="hello"} 1637060
telemt_user_connections_current{user="hello"} 1208
telemt_user_octets_from_client{user="hello"} 25351527880 (23.61 GB)
telemt_user_octets_to_client{user="hello"} 563201366448 (524.52 GB)
telemt_user_unique_ips_current{user="hello"} 348
telemt_user_unique_ips_recent_window{user="hello"} 154
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 79898.1 (22h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 743852
telemt_connections_bad_total 10391
telemt_handshake_timeouts_total 30093
telemt_upstream_connect_attempt_total 20256
telemt_upstream_connect_success_total 20227
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 20256
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10695
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9448
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3377
telemt_me_reconnect_attempts_total 14674
telemt_me_reconnect_success_total 14586
telemt_me_reader_eof_total 15507
telemt_me_idle_close_by_peer_total 15507
telemt_me_route_drop_no_conn_total 238752
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 670704
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2909
telemt_desync_full_logged_total 890
telemt_desync_suppressed_total 2019
telemt_desync_frames_bucket_total{bucket="1_2"} 1126
telemt_desync_frames_bucket_total{bucket="3_10"} 964
telemt_desync_frames_bucket_total{bucket="gt_10"} 819
telemt_pool_swap_total 79
telemt_me_writer_removed_unexpected_total 14738
telemt_me_writer_restored_same_endpoint_total 14577
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 152
telemt_user_connections_total{user="hello"} 672584
telemt_user_connections_current{user="hello"} 395
telemt_user_octets_from_client{user="hello"} 11433359824 (10.65 GB)
telemt_user_octets_to_client{user="hello"} 252989231715 (235.61 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 124
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 79897.9 (22h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1537251
telemt_connections_bad_total 7278
telemt_handshake_timeouts_total 104593
telemt_upstream_connect_attempt_total 18807
telemt_upstream_connect_success_total 18802
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 18807
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10117
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8612
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1190
telemt_me_reconnect_attempts_total 15692
telemt_me_reconnect_success_total 14446
telemt_me_reader_eof_total 15240
telemt_me_idle_close_by_peer_total 15239
telemt_me_route_drop_no_conn_total 508038
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1182182
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4790
telemt_desync_full_logged_total 1477
telemt_desync_suppressed_total 3313
telemt_desync_frames_bucket_total{bucket="1_2"} 758
telemt_desync_frames_bucket_total{bucket="3_10"} 1736
telemt_desync_frames_bucket_total{bucket="gt_10"} 2296
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 14579
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 14405
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 133
telemt_user_connections_total{user="hello"} 1181792
telemt_user_connections_current{user="hello"} 683
telemt_user_octets_from_client{user="hello"} 18412931424 (17.15 GB)
telemt_user_octets_to_client{user="hello"} 439644953857 (409.45 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 213
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 79898.2 (22h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 942422
telemt_connections_bad_total 12967
telemt_handshake_timeouts_total 70328
telemt_upstream_connect_attempt_total 20455
telemt_upstream_connect_success_total 20374
telemt_upstream_connect_fail_total 81
telemt_upstream_connect_attempts_per_request{bucket="1"} 20455
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11415
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8946
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 81
telemt_me_keepalive_timeout_total 1659
telemt_me_reconnect_attempts_total 24111
telemt_me_reconnect_success_total 16386
telemt_me_reader_eof_total 17505
telemt_me_idle_close_by_peer_total 17505
telemt_me_route_drop_no_conn_total 334599
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 816010
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1749
telemt_desync_full_logged_total 586
telemt_desync_suppressed_total 1163
telemt_desync_frames_bucket_total{bucket="1_2"} 491
telemt_desync_frames_bucket_total{bucket="3_10"} 677
telemt_desync_frames_bucket_total{bucket="gt_10"} 581
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 16761
telemt_me_refill_failed_total 239
telemt_me_writer_restored_same_endpoint_total 16365
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 375
telemt_user_connections_total{user="hello"} 815364
telemt_user_connections_current{user="hello"} 452
telemt_user_octets_from_client{user="hello"} 12740363748 (11.87 GB)
telemt_user_octets_to_client{user="hello"} 333839125904 (310.91 GB)
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 79898.1 (22h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1059761
telemt_connections_bad_total 12339
telemt_handshake_timeouts_total 8760
telemt_upstream_connect_attempt_total 24787
telemt_upstream_connect_success_total 24484
telemt_upstream_connect_fail_total 303
telemt_upstream_connect_attempts_per_request{bucket="1"} 24787
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12507
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11844
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 125
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 303
telemt_me_keepalive_timeout_total 1405
telemt_me_reconnect_attempts_total 31514
telemt_me_reconnect_success_total 20477
telemt_me_reader_eof_total 21511
telemt_me_idle_close_by_peer_total 21511
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 396299
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 972011
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3639
telemt_desync_full_logged_total 1270
telemt_desync_suppressed_total 2369
telemt_desync_frames_bucket_total{bucket="1_2"} 1028
telemt_desync_frames_bucket_total{bucket="3_10"} 1212
telemt_desync_frames_bucket_total{bucket="gt_10"} 1399
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 21057
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 20433
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 580
telemt_user_connections_total{user="hello"} 971881
telemt_user_connections_current{user="hello"} 613
telemt_user_octets_from_client{user="hello"} 12044109660 (11.22 GB)
telemt_user_octets_to_client{user="hello"} 335370617504 (312.34 GB)
telemt_user_unique_ips_current{user="hello"} 172
telemt_user_unique_ips_recent_window{user="hello"} 80
```