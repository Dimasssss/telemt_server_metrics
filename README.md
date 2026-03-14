# Server Metrics 2026-03-14 09:44:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 186347.3 (51h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5319318
telemt_connections_bad_total 50568
telemt_handshake_timeouts_total 118947
telemt_upstream_connect_attempt_total 39032
telemt_upstream_connect_success_total 38779
telemt_upstream_connect_fail_total 253
telemt_upstream_connect_attempts_per_request{bucket="1"} 39032
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21025
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17601
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 153
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 253
telemt_me_keepalive_timeout_total 7536
telemt_me_reconnect_attempts_total 38407
telemt_me_reconnect_success_total 27192
telemt_me_reader_eof_total 29176
telemt_me_idle_close_by_peer_total 29175
telemt_me_route_drop_no_conn_total 2010780
telemt_me_route_drop_channel_closed_total 29
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4874878
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 18650
telemt_desync_full_logged_total 5099
telemt_desync_suppressed_total 13551
telemt_desync_frames_bucket_total{bucket="1_2"} 4586
telemt_desync_frames_bucket_total{bucket="3_10"} 7115
telemt_desync_frames_bucket_total{bucket="gt_10"} 6949
telemt_pool_swap_total 161
telemt_me_writer_removed_unexpected_total 27940
telemt_me_refill_failed_total 345
telemt_me_writer_restored_same_endpoint_total 27179
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 748
telemt_user_connections_total{user="hello"} 4876352
telemt_user_connections_current{user="hello"} 1670
telemt_user_octets_from_client{user="hello"} 74740742648 (69.61 GB)
telemt_user_octets_to_client{user="hello"} 1557036187765 (1.42 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 459
telemt_user_unique_ips_recent_window{user="hello"} 212
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 86011.3 (23h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 962396
telemt_connections_bad_total 55383
telemt_handshake_timeouts_total 20017
telemt_upstream_connect_attempt_total 22724
telemt_upstream_connect_success_total 22435
telemt_upstream_connect_fail_total 289
telemt_upstream_connect_attempts_per_request{bucket="1"} 22724
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12191
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9954
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 41
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 249
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 289
telemt_me_keepalive_timeout_total 2226
telemt_me_reconnect_attempts_total 25995
telemt_me_reconnect_success_total 16123
telemt_me_reader_eof_total 17292
telemt_me_idle_close_by_peer_total 17291
telemt_me_route_drop_no_conn_total 321778
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 784029
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2190
telemt_desync_full_logged_total 690
telemt_desync_suppressed_total 1500
telemt_desync_frames_bucket_total{bucket="1_2"} 498
telemt_desync_frames_bucket_total{bucket="3_10"} 941
telemt_desync_frames_bucket_total{bucket="gt_10"} 751
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 16661
telemt_me_refill_failed_total 302
telemt_me_writer_restored_same_endpoint_total 16115
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 538
telemt_user_connections_total{user="hello"} 785926
telemt_user_connections_current{user="hello"} 595
telemt_user_octets_from_client{user="hello"} 8368665017 (7.79 GB)
telemt_user_octets_to_client{user="hello"} 271292719180 (252.66 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 187
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 215968.0 (59h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3787641
telemt_connections_bad_total 44534
telemt_handshake_timeouts_total 250097
telemt_upstream_connect_attempt_total 48696
telemt_upstream_connect_success_total 48675
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 48696
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25707
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22713
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 248
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10909
telemt_me_reconnect_attempts_total 42626
telemt_me_reconnect_success_total 37630
telemt_me_reader_eof_total 39955
telemt_me_idle_close_by_peer_total 39954
telemt_me_route_drop_no_conn_total 1301590
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3164408
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10193
telemt_desync_full_logged_total 3465
telemt_desync_suppressed_total 6728
telemt_desync_frames_bucket_total{bucket="1_2"} 1828
telemt_desync_frames_bucket_total{bucket="3_10"} 3697
telemt_desync_frames_bucket_total{bucket="gt_10"} 4668
telemt_pool_swap_total 202
telemt_pool_stale_pick_total 3
telemt_me_writer_removed_unexpected_total 38153
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 37589
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 523
telemt_user_connections_total{user="hello"} 3163577
telemt_user_connections_current{user="hello"} 945
telemt_user_octets_from_client{user="hello"} 53514604260 (49.84 GB)
telemt_user_octets_to_client{user="hello"} 1133910026125 (1.03 TB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 265
telemt_user_unique_ips_recent_window{user="hello"} 138
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 215970.6 (59h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2503207
telemt_connections_bad_total 23387
telemt_handshake_timeouts_total 313206
telemt_upstream_connect_attempt_total 66795
telemt_upstream_connect_success_total 64296
telemt_upstream_connect_fail_total 2362
telemt_upstream_connect_attempts_per_request{bucket="1"} 66521
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38380
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25750
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2361
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20644
telemt_me_reconnect_attempts_total 58195
telemt_me_reconnect_success_total 46544
telemt_me_reader_eof_total 49900
telemt_me_idle_close_by_peer_total 49893
telemt_me_route_drop_no_conn_total 838056
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1962680
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4029
telemt_desync_full_logged_total 1318
telemt_desync_suppressed_total 2711
telemt_desync_frames_bucket_total{bucket="1_2"} 1134
telemt_desync_frames_bucket_total{bucket="3_10"} 1646
telemt_desync_frames_bucket_total{bucket="gt_10"} 1249
telemt_pool_swap_total 188
telemt_me_writer_removed_unexpected_total 47309
telemt_me_refill_failed_total 355
telemt_me_writer_restored_same_endpoint_total 46520
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 765
telemt_user_connections_total{user="hello"} 1968858
telemt_user_connections_current{user="hello"} 496
telemt_user_octets_from_client{user="hello"} 29422547415 (27.40 GB)
telemt_user_octets_to_client{user="hello"} 710931528422 (662.11 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 85403.8 (23h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 947185
telemt_connections_bad_total 14385
telemt_handshake_timeouts_total 12367
telemt_upstream_connect_attempt_total 21612
telemt_upstream_connect_success_total 21034
telemt_upstream_connect_fail_total 578
telemt_upstream_connect_attempts_per_request{bucket="1"} 21612
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10039
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10969
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 578
telemt_me_keepalive_timeout_total 1681
telemt_me_reconnect_attempts_total 69568
telemt_me_reconnect_success_total 16789
telemt_me_reader_eof_total 18847
telemt_me_idle_close_by_peer_total 18846
telemt_me_route_drop_no_conn_total 362587
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 878496
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2322
telemt_desync_full_logged_total 725
telemt_desync_suppressed_total 1597
telemt_desync_frames_bucket_total{bucket="1_2"} 771
telemt_desync_frames_bucket_total{bucket="3_10"} 871
telemt_desync_frames_bucket_total{bucket="gt_10"} 680
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 18593
telemt_me_refill_failed_total 1644
telemt_me_writer_restored_same_endpoint_total 16784
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1804
telemt_user_connections_total{user="hello"} 878440
telemt_user_connections_current{user="hello"} 697
telemt_user_octets_from_client{user="hello"} 15600174684 (14.53 GB)
telemt_user_octets_to_client{user="hello"} 295040876560 (274.78 GB)
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 92
```