# Server Metrics 2026-03-13 20:01:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 136956.7 (38h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4365386
telemt_connections_bad_total 37808
telemt_handshake_timeouts_total 105851
telemt_upstream_connect_attempt_total 28735
telemt_upstream_connect_success_total 28539
telemt_upstream_connect_fail_total 196
telemt_upstream_connect_attempts_per_request{bucket="1"} 28735
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15738
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12663
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 138
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 196
telemt_me_keepalive_timeout_total 6532
telemt_me_reconnect_attempts_total 29467
telemt_me_reconnect_success_total 19351
telemt_me_reader_eof_total 20765
telemt_me_idle_close_by_peer_total 20764
telemt_me_route_drop_no_conn_total 1641369
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3994269
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 15790
telemt_desync_full_logged_total 4209
telemt_desync_suppressed_total 11581
telemt_desync_frames_bucket_total{bucket="1_2"} 3942
telemt_desync_frames_bucket_total{bucket="3_10"} 6011
telemt_desync_frames_bucket_total{bucket="gt_10"} 5837
telemt_pool_swap_total 116
telemt_me_writer_removed_unexpected_total 19945
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 19338
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 594
telemt_user_connections_total{user="hello"} 3996431
telemt_user_connections_current{user="hello"} 1309
telemt_user_octets_from_client{user="hello"} 58176757412 (54.18 GB)
telemt_user_octets_to_client{user="hello"} 1260937054821 (1.15 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 374
telemt_user_unique_ips_recent_window{user="hello"} 176
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 36620.6 (10h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 526146
telemt_connections_bad_total 40831
telemt_handshake_timeouts_total 12000
telemt_upstream_connect_attempt_total 10605
telemt_upstream_connect_success_total 10391
telemt_upstream_connect_fail_total 214
telemt_upstream_connect_attempts_per_request{bucket="1"} 10605
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6091
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4089
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 21
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 190
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 214
telemt_me_keepalive_timeout_total 1872
telemt_me_reconnect_attempts_total 9938
telemt_me_reconnect_success_total 6523
telemt_me_reader_eof_total 6900
telemt_me_idle_close_by_peer_total 6899
telemt_me_route_drop_no_conn_total 196252
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 456156
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1551
telemt_desync_full_logged_total 418
telemt_desync_suppressed_total 1133
telemt_desync_frames_bucket_total{bucket="1_2"} 328
telemt_desync_frames_bucket_total{bucket="3_10"} 687
telemt_desync_frames_bucket_total{bucket="gt_10"} 536
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 6719
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 6515
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 196
telemt_user_connections_total{user="hello"} 458086
telemt_user_connections_current{user="hello"} 505
telemt_user_octets_from_client{user="hello"} 4903946129 (4.57 GB)
telemt_user_octets_to_client{user="hello"} 144968578252 (135.01 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 166577.4 (46h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3184090
telemt_connections_bad_total 29307
telemt_handshake_timeouts_total 213690
telemt_upstream_connect_attempt_total 36885
telemt_upstream_connect_success_total 36868
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 36885
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19105
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17584
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 173
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 10188
telemt_me_reconnect_attempts_total 30825
telemt_me_reconnect_success_total 28257
telemt_me_reader_eof_total 29948
telemt_me_idle_close_by_peer_total 29947
telemt_me_route_drop_no_conn_total 1090007
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2635920
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8751
telemt_desync_full_logged_total 2906
telemt_desync_suppressed_total 5845
telemt_desync_frames_bucket_total{bucket="1_2"} 1440
telemt_desync_frames_bucket_total{bucket="3_10"} 3204
telemt_desync_frames_bucket_total{bucket="gt_10"} 4107
telemt_pool_swap_total 156
telemt_me_writer_removed_unexpected_total 28595
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 28216
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 338
telemt_user_connections_total{user="hello"} 2635202
telemt_user_connections_current{user="hello"} 626
telemt_user_octets_from_client{user="hello"} 43537315376 (40.55 GB)
telemt_user_octets_to_client{user="hello"} 928798483729 (865.01 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 214
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 166577.8 (46h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2059623
telemt_connections_bad_total 22236
telemt_handshake_timeouts_total 191775
telemt_upstream_connect_attempt_total 52154
telemt_upstream_connect_success_total 49717
telemt_upstream_connect_fail_total 2300
telemt_upstream_connect_attempts_per_request{bucket="1"} 51880
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29959
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19594
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 164
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2299
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20199
telemt_me_reconnect_attempts_total 43402
telemt_me_reconnect_success_total 34394
telemt_me_reader_eof_total 36924
telemt_me_idle_close_by_peer_total 36917
telemt_me_route_drop_no_conn_total 728972
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1699145
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3665
telemt_desync_full_logged_total 1171
telemt_desync_suppressed_total 2494
telemt_desync_frames_bucket_total{bucket="1_2"} 966
telemt_desync_frames_bucket_total{bucket="3_10"} 1522
telemt_desync_frames_bucket_total{bucket="gt_10"} 1177
telemt_pool_swap_total 145
telemt_me_writer_removed_unexpected_total 34966
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 34370
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 572
telemt_user_connections_total{user="hello"} 1705014
telemt_user_connections_current{user="hello"} 593
telemt_user_octets_from_client{user="hello"} 26236892651 (24.44 GB)
telemt_user_octets_to_client{user="hello"} 640926357610 (596.91 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 178
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 36013.1 (10h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 565155
telemt_connections_bad_total 5701
telemt_handshake_timeouts_total 5472
telemt_upstream_connect_attempt_total 7803
telemt_upstream_connect_success_total 7551
telemt_upstream_connect_fail_total 252
telemt_upstream_connect_attempts_per_request{bucket="1"} 7803
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3588
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3943
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 252
telemt_me_keepalive_timeout_total 964
telemt_me_reconnect_attempts_total 26689
telemt_me_reconnect_success_total 5751
telemt_me_reader_eof_total 6516
telemt_me_idle_close_by_peer_total 6515
telemt_me_route_drop_no_conn_total 214440
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 529801
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1463
telemt_desync_full_logged_total 455
telemt_desync_suppressed_total 1008
telemt_desync_frames_bucket_total{bucket="1_2"} 441
telemt_desync_frames_bucket_total{bucket="3_10"} 586
telemt_desync_frames_bucket_total{bucket="gt_10"} 436
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 6452
telemt_me_refill_failed_total 652
telemt_me_writer_restored_same_endpoint_total 5747
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 701
telemt_user_connections_total{user="hello"} 529757
telemt_user_connections_current{user="hello"} 617
telemt_user_octets_from_client{user="hello"} 6174213744 (5.75 GB)
telemt_user_octets_to_client{user="hello"} 169344103912 (157.71 GB)
telemt_user_unique_ips_current{user="hello"} 162
telemt_user_unique_ips_recent_window{user="hello"} 81
```