# Server Metrics 2026-03-12 20:47:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 53341.4 (14h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1820647
telemt_connections_bad_total 20725
telemt_handshake_timeouts_total 20000
telemt_upstream_connect_attempt_total 10385
telemt_upstream_connect_success_total 10324
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 10385
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5391
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4898
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_keepalive_timeout_total 583
telemt_me_reconnect_attempts_total 16465
telemt_me_reconnect_success_total 7615
telemt_me_reader_eof_total 8240
telemt_me_idle_close_by_peer_total 8239
telemt_me_route_drop_no_conn_total 715953
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1699467
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8323
telemt_desync_full_logged_total 2150
telemt_desync_suppressed_total 6173
telemt_desync_frames_bucket_total{bucket="1_2"} 2182
telemt_desync_frames_bucket_total{bucket="3_10"} 3003
telemt_desync_frames_bucket_total{bucket="gt_10"} 3138
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 8002
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 7602
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 387
telemt_user_connections_total{user="hello"} 1698953
telemt_user_connections_current{user="hello"} 1025
telemt_user_octets_from_client{user="hello"} 26100202356 (24.31 GB)
telemt_user_octets_to_client{user="hello"} 594543841372 (553.71 GB)
telemt_user_unique_ips_current{user="hello"} 292
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 82962.0 (23h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 765069
telemt_connections_bad_total 11221
telemt_handshake_timeouts_total 30453
telemt_upstream_connect_attempt_total 21000
telemt_upstream_connect_success_total 20971
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 21000
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11083
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9801
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 87
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3387
telemt_me_reconnect_attempts_total 15245
telemt_me_reconnect_success_total 15154
telemt_me_reader_eof_total 16120
telemt_me_idle_close_by_peer_total 16120
telemt_me_route_drop_no_conn_total 246384
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 690207
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2938
telemt_desync_full_logged_total 901
telemt_desync_suppressed_total 2037
telemt_desync_frames_bucket_total{bucket="1_2"} 1139
telemt_desync_frames_bucket_total{bucket="3_10"} 973
telemt_desync_frames_bucket_total{bucket="gt_10"} 826
telemt_pool_swap_total 83
telemt_me_writer_removed_unexpected_total 15309
telemt_me_writer_restored_same_endpoint_total 15145
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 155
telemt_user_connections_total{user="hello"} 692079
telemt_user_connections_current{user="hello"} 381
telemt_user_octets_from_client{user="hello"} 11789718968 (10.98 GB)
telemt_user_octets_to_client{user="hello"} 264764463603 (246.58 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 82961.9 (23h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1580370
telemt_connections_bad_total 7539
telemt_handshake_timeouts_total 108434
telemt_upstream_connect_attempt_total 19475
telemt_upstream_connect_success_total 19469
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 19475
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10477
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8919
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 1206
telemt_me_reconnect_attempts_total 16188
telemt_me_reconnect_success_total 14941
telemt_me_reader_eof_total 15774
telemt_me_idle_close_by_peer_total 15773
telemt_me_route_drop_no_conn_total 521984
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1220358
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4837
telemt_desync_full_logged_total 1487
telemt_desync_suppressed_total 3350
telemt_desync_frames_bucket_total{bucket="1_2"} 770
telemt_desync_frames_bucket_total{bucket="3_10"} 1751
telemt_desync_frames_bucket_total{bucket="gt_10"} 2316
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 15082
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 14900
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 141
telemt_user_connections_total{user="hello"} 1219967
telemt_user_connections_current{user="hello"} 548
telemt_user_octets_from_client{user="hello"} 19195305824 (17.88 GB)
telemt_user_octets_to_client{user="hello"} 455237554221 (423.97 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 186
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 82962.3 (23h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 971535
telemt_connections_bad_total 12970
telemt_handshake_timeouts_total 70746
telemt_upstream_connect_attempt_total 21176
telemt_upstream_connect_success_total 21090
telemt_upstream_connect_fail_total 86
telemt_upstream_connect_attempts_per_request{bucket="1"} 21176
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11831
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9245
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 86
telemt_me_keepalive_timeout_total 1671
telemt_me_reconnect_attempts_total 24653
telemt_me_reconnect_success_total 16927
telemt_me_reader_eof_total 18079
telemt_me_idle_close_by_peer_total 18079
telemt_me_route_drop_no_conn_total 346577
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 844065
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1806
telemt_desync_full_logged_total 599
telemt_desync_suppressed_total 1207
telemt_desync_frames_bucket_total{bucket="1_2"} 506
telemt_desync_frames_bucket_total{bucket="3_10"} 695
telemt_desync_frames_bucket_total{bucket="gt_10"} 605
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 17303
telemt_me_refill_failed_total 239
telemt_me_writer_restored_same_endpoint_total 16906
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 376
telemt_user_connections_total{user="hello"} 843415
telemt_user_connections_current{user="hello"} 328
telemt_user_octets_from_client{user="hello"} 13212069304 (12.30 GB)
telemt_user_octets_to_client{user="hello"} 344571396532 (320.91 GB)
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 82962.2 (23h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1090156
telemt_connections_bad_total 12469
telemt_handshake_timeouts_total 8990
telemt_upstream_connect_attempt_total 25719
telemt_upstream_connect_success_total 25404
telemt_upstream_connect_fail_total 315
telemt_upstream_connect_attempts_per_request{bucket="1"} 25719
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12975
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12291
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 130
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 315
telemt_me_keepalive_timeout_total 1422
telemt_me_reconnect_attempts_total 32261
telemt_me_reconnect_success_total 21223
telemt_me_reader_eof_total 22302
telemt_me_idle_close_by_peer_total 22302
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 407836
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1000904
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3754
telemt_desync_full_logged_total 1313
telemt_desync_suppressed_total 2441
telemt_desync_frames_bucket_total{bucket="1_2"} 1088
telemt_desync_frames_bucket_total{bucket="3_10"} 1242
telemt_desync_frames_bucket_total{bucket="gt_10"} 1424
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 21810
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 21179
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 587
telemt_user_connections_total{user="hello"} 1000767
telemt_user_connections_current{user="hello"} 458
telemt_user_octets_from_client{user="hello"} 12449719388 (11.59 GB)
telemt_user_octets_to_client{user="hello"} 352977728792 (328.74 GB)
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 54
```