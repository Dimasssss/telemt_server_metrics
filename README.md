# Server Metrics 2026-03-14 07:05:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 176823.6 (49h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4983991
telemt_connections_bad_total 40206
telemt_handshake_timeouts_total 113232
telemt_upstream_connect_attempt_total 37083
telemt_upstream_connect_success_total 36840
telemt_upstream_connect_fail_total 243
telemt_upstream_connect_attempts_per_request{bucket="1"} 37083
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20011
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16679
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 243
telemt_me_keepalive_timeout_total 7337
telemt_me_reconnect_attempts_total 35861
telemt_me_reconnect_success_total 25710
telemt_me_reader_eof_total 27592
telemt_me_idle_close_by_peer_total 27591
telemt_me_route_drop_no_conn_total 1886867
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4572233
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 17464
telemt_desync_full_logged_total 4746
telemt_desync_suppressed_total 12718
telemt_desync_frames_bucket_total{bucket="1_2"} 4363
telemt_desync_frames_bucket_total{bucket="3_10"} 6648
telemt_desync_frames_bucket_total{bucket="gt_10"} 6453
telemt_pool_swap_total 156
telemt_me_writer_removed_unexpected_total 26396
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 25697
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 686
telemt_user_connections_total{user="hello"} 4573713
telemt_user_connections_current{user="hello"} 1677
telemt_user_octets_from_client{user="hello"} 67066864600 (62.46 GB)
telemt_user_octets_to_client{user="hello"} 1443816045589 (1.31 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 457
telemt_user_unique_ips_recent_window{user="hello"} 218
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 76487.5 (21h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 833795
telemt_connections_bad_total 53815
telemt_handshake_timeouts_total 15243
telemt_upstream_connect_attempt_total 20655
telemt_upstream_connect_success_total 20384
telemt_upstream_connect_fail_total 271
telemt_upstream_connect_attempts_per_request{bucket="1"} 20655
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11184
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8935
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 232
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 271
telemt_me_keepalive_timeout_total 2144
telemt_me_reconnect_attempts_total 18030
telemt_me_reconnect_success_total 14565
telemt_me_reader_eof_total 15479
telemt_me_idle_close_by_peer_total 15478
telemt_me_route_drop_no_conn_total 273951
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 665158
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1946
telemt_desync_full_logged_total 594
telemt_desync_suppressed_total 1352
telemt_desync_frames_bucket_total{bucket="1_2"} 409
telemt_desync_frames_bucket_total{bucket="3_10"} 866
telemt_desync_frames_bucket_total{bucket="gt_10"} 671
telemt_pool_swap_total 67
telemt_me_writer_removed_unexpected_total 14880
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 14557
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 315
telemt_user_connections_total{user="hello"} 667072
telemt_user_connections_current{user="hello"} 576
telemt_user_octets_from_client{user="hello"} 6998902433 (6.52 GB)
telemt_user_octets_to_client{user="hello"} 227584863860 (211.95 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 178
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 206444.2 (57h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3575973
telemt_connections_bad_total 42014
telemt_handshake_timeouts_total 234940
telemt_upstream_connect_attempt_total 46623
telemt_upstream_connect_success_total 46602
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 46623
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24562
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21792
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 241
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10704
telemt_me_reconnect_attempts_total 40993
telemt_me_reconnect_success_total 36018
telemt_me_reader_eof_total 38262
telemt_me_idle_close_by_peer_total 38261
telemt_me_route_drop_no_conn_total 1222703
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2981378
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9824
telemt_desync_full_logged_total 3299
telemt_desync_suppressed_total 6525
telemt_desync_frames_bucket_total{bucket="1_2"} 1713
telemt_desync_frames_bucket_total{bucket="3_10"} 3552
telemt_desync_frames_bucket_total{bucket="gt_10"} 4559
telemt_pool_swap_total 196
telemt_me_writer_removed_unexpected_total 36517
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 35977
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 499
telemt_user_connections_total{user="hello"} 2980527
telemt_user_connections_current{user="hello"} 807
telemt_user_octets_from_client{user="hello"} 49948177616 (46.52 GB)
telemt_user_octets_to_client{user="hello"} 1063975696485 (990.90 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 264
telemt_user_unique_ips_recent_window{user="hello"} 127
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 206446.8 (57h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2382176
telemt_connections_bad_total 23301
telemt_handshake_timeouts_total 284034
telemt_upstream_connect_attempt_total 64294
telemt_upstream_connect_success_total 61805
telemt_upstream_connect_fail_total 2352
telemt_upstream_connect_attempts_per_request{bucket="1"} 64020
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36878
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24761
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2351
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20517
telemt_me_reconnect_attempts_total 53555
telemt_me_reconnect_success_total 44509
telemt_me_reader_eof_total 47706
telemt_me_idle_close_by_peer_total 47699
telemt_me_route_drop_no_conn_total 801959
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1877490
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3923
telemt_desync_full_logged_total 1273
telemt_desync_suppressed_total 2650
telemt_desync_frames_bucket_total{bucket="1_2"} 1074
telemt_desync_frames_bucket_total{bucket="3_10"} 1618
telemt_desync_frames_bucket_total{bucket="gt_10"} 1231
telemt_pool_swap_total 183
telemt_me_writer_removed_unexpected_total 45175
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 44485
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 666
telemt_user_connections_total{user="hello"} 1883564
telemt_user_connections_current{user="hello"} 363
telemt_user_octets_from_client{user="hello"} 28364738255 (26.42 GB)
telemt_user_octets_to_client{user="hello"} 691868399566 (644.35 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 75880.4 (21h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 806040
telemt_connections_bad_total 8265
telemt_handshake_timeouts_total 9438
telemt_upstream_connect_attempt_total 19364
telemt_upstream_connect_success_total 18838
telemt_upstream_connect_fail_total 526
telemt_upstream_connect_attempts_per_request{bucket="1"} 19364
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9009
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9803
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 526
telemt_me_keepalive_timeout_total 1585
telemt_me_reconnect_attempts_total 60351
telemt_me_reconnect_success_total 15044
telemt_me_reader_eof_total 16826
telemt_me_idle_close_by_peer_total 16825
telemt_me_route_drop_no_conn_total 310562
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 753099
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1829
telemt_desync_full_logged_total 586
telemt_desync_suppressed_total 1243
telemt_desync_frames_bucket_total{bucket="1_2"} 540
telemt_desync_frames_bucket_total{bucket="3_10"} 707
telemt_desync_frames_bucket_total{bucket="gt_10"} 582
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 16588
telemt_me_refill_failed_total 1411
telemt_me_writer_restored_same_endpoint_total 15039
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1544
telemt_user_connections_total{user="hello"} 752960
telemt_user_connections_current{user="hello"} 676
telemt_user_octets_from_client{user="hello"} 13400001404 (12.48 GB)
telemt_user_octets_to_client{user="hello"} 254247880716 (236.79 GB)
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 100
```