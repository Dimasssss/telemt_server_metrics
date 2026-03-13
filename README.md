# Server Metrics 2026-03-13 19:56:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 136651.3 (37h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4357424
telemt_connections_bad_total 37805
telemt_handshake_timeouts_total 105797
telemt_upstream_connect_attempt_total 28639
telemt_upstream_connect_success_total 28445
telemt_upstream_connect_fail_total 194
telemt_upstream_connect_attempts_per_request{bucket="1"} 28639
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15694
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12614
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 137
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 194
telemt_me_keepalive_timeout_total 6532
telemt_me_reconnect_attempts_total 29417
telemt_me_reconnect_success_total 19301
telemt_me_reader_eof_total 20708
telemt_me_idle_close_by_peer_total 20707
telemt_me_route_drop_no_conn_total 1638064
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3986545
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 15751
telemt_desync_full_logged_total 4197
telemt_desync_suppressed_total 11554
telemt_desync_frames_bucket_total{bucket="1_2"} 3931
telemt_desync_frames_bucket_total{bucket="3_10"} 6000
telemt_desync_frames_bucket_total{bucket="gt_10"} 5820
telemt_pool_swap_total 115
telemt_me_writer_removed_unexpected_total 19895
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 19288
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 594
telemt_user_connections_total{user="hello"} 3988707
telemt_user_connections_current{user="hello"} 1431
telemt_user_octets_from_client{user="hello"} 57962329852 (53.98 GB)
telemt_user_octets_to_client{user="hello"} 1258073081669 (1.14 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 374
telemt_user_unique_ips_recent_window{user="hello"} 173
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 36315.2 (10h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 522914
telemt_connections_bad_total 40588
telemt_handshake_timeouts_total 11947
telemt_upstream_connect_attempt_total 10571
telemt_upstream_connect_success_total 10357
telemt_upstream_connect_fail_total 214
telemt_upstream_connect_attempts_per_request{bucket="1"} 10571
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6073
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4075
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 20
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 189
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 214
telemt_me_keepalive_timeout_total 1870
telemt_me_reconnect_attempts_total 9904
telemt_me_reconnect_success_total 6489
telemt_me_reader_eof_total 6866
telemt_me_idle_close_by_peer_total 6865
telemt_me_route_drop_no_conn_total 195369
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 453557
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
telemt_me_writer_removed_unexpected_total 6685
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 6481
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 196
telemt_user_connections_total{user="hello"} 455487
telemt_user_connections_current{user="hello"} 510
telemt_user_octets_from_client{user="hello"} 4879258773 (4.54 GB)
telemt_user_octets_to_client{user="hello"} 143820349188 (133.94 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 166271.9 (46h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3179530
telemt_connections_bad_total 29304
telemt_handshake_timeouts_total 213453
telemt_upstream_connect_attempt_total 36847
telemt_upstream_connect_success_total 36830
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 36847
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19086
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17569
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 169
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 10188
telemt_me_reconnect_attempts_total 30806
telemt_me_reconnect_success_total 28238
telemt_me_reader_eof_total 29929
telemt_me_idle_close_by_peer_total 29928
telemt_me_route_drop_no_conn_total 1087812
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2631632
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
telemt_me_writer_removed_unexpected_total 28576
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 28197
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 338
telemt_user_connections_total{user="hello"} 2630914
telemt_user_connections_current{user="hello"} 721
telemt_user_octets_from_client{user="hello"} 43516462236 (40.53 GB)
telemt_user_octets_to_client{user="hello"} 926586124117 (862.95 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 230
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 166272.4 (46h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2054313
telemt_connections_bad_total 22122
telemt_handshake_timeouts_total 190319
telemt_upstream_connect_attempt_total 52103
telemt_upstream_connect_success_total 49667
telemt_upstream_connect_fail_total 2299
telemt_upstream_connect_attempts_per_request{bucket="1"} 51829
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29931
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19572
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 164
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2298
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20195
telemt_me_reconnect_attempts_total 43376
telemt_me_reconnect_success_total 34369
telemt_me_reader_eof_total 36898
telemt_me_idle_close_by_peer_total 36891
telemt_me_route_drop_no_conn_total 727614
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1695757
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3658
telemt_desync_full_logged_total 1167
telemt_desync_suppressed_total 2491
telemt_desync_frames_bucket_total{bucket="1_2"} 965
telemt_desync_frames_bucket_total{bucket="3_10"} 1520
telemt_desync_frames_bucket_total{bucket="gt_10"} 1173
telemt_pool_swap_total 145
telemt_me_writer_removed_unexpected_total 34940
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 34345
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 571
telemt_user_connections_total{user="hello"} 1701626
telemt_user_connections_current{user="hello"} 588
telemt_user_octets_from_client{user="hello"} 26078597319 (24.29 GB)
telemt_user_octets_to_client{user="hello"} 640011864826 (596.06 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 35707.8 (9h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 561752
telemt_connections_bad_total 5700
telemt_handshake_timeouts_total 5460
telemt_upstream_connect_attempt_total 7751
telemt_upstream_connect_success_total 7499
telemt_upstream_connect_fail_total 252
telemt_upstream_connect_attempts_per_request{bucket="1"} 7751
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3561
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3918
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 252
telemt_me_keepalive_timeout_total 964
telemt_me_reconnect_attempts_total 26637
telemt_me_reconnect_success_total 5700
telemt_me_reader_eof_total 6463
telemt_me_idle_close_by_peer_total 6462
telemt_me_route_drop_no_conn_total 213224
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 526524
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1456
telemt_desync_full_logged_total 453
telemt_desync_suppressed_total 1003
telemt_desync_frames_bucket_total{bucket="1_2"} 440
telemt_desync_frames_bucket_total{bucket="3_10"} 583
telemt_desync_frames_bucket_total{bucket="gt_10"} 433
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 6399
telemt_me_refill_failed_total 652
telemt_me_writer_restored_same_endpoint_total 5696
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 699
telemt_user_connections_total{user="hello"} 526485
telemt_user_connections_current{user="hello"} 512
telemt_user_octets_from_client{user="hello"} 6145198520 (5.72 GB)
telemt_user_octets_to_client{user="hello"} 168083133360 (156.54 GB)
telemt_user_unique_ips_current{user="hello"} 160
telemt_user_unique_ips_recent_window{user="hello"} 69
```