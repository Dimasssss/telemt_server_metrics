# Server Metrics 2026-03-14 06:19:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 174054.9 (48h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4901319
telemt_connections_bad_total 40034
telemt_handshake_timeouts_total 112676
telemt_upstream_connect_attempt_total 36590
telemt_upstream_connect_success_total 36352
telemt_upstream_connect_fail_total 238
telemt_upstream_connect_attempts_per_request{bucket="1"} 36590
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19761
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16443
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 148
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 238
telemt_me_keepalive_timeout_total 7313
telemt_me_reconnect_attempts_total 35502
telemt_me_reconnect_success_total 25353
telemt_me_reader_eof_total 27211
telemt_me_idle_close_by_peer_total 27210
telemt_me_route_drop_no_conn_total 1857521
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4498730
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 17279
telemt_desync_full_logged_total 4668
telemt_desync_suppressed_total 12611
telemt_desync_frames_bucket_total{bucket="1_2"} 4311
telemt_desync_frames_bucket_total{bucket="3_10"} 6597
telemt_desync_frames_bucket_total{bucket="gt_10"} 6371
telemt_pool_swap_total 153
telemt_me_writer_removed_unexpected_total 26033
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 25340
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 680
telemt_user_connections_total{user="hello"} 4500246
telemt_user_connections_current{user="hello"} 1133
telemt_user_octets_from_client{user="hello"} 65689642016 (61.18 GB)
telemt_user_octets_to_client{user="hello"} 1419763980753 (1.29 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 369
telemt_user_unique_ips_recent_window{user="hello"} 160
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 73718.8 (20h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 803141
telemt_connections_bad_total 53805
telemt_handshake_timeouts_total 14682
telemt_upstream_connect_attempt_total 20012
telemt_upstream_connect_success_total 19742
telemt_upstream_connect_fail_total 270
telemt_upstream_connect_attempts_per_request{bucket="1"} 20012
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10867
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8614
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 32
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 229
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 270
telemt_me_keepalive_timeout_total 2139
telemt_me_reconnect_attempts_total 17518
telemt_me_reconnect_success_total 14056
telemt_me_reader_eof_total 14940
telemt_me_idle_close_by_peer_total 14939
telemt_me_route_drop_no_conn_total 262836
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 636333
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1868
telemt_desync_full_logged_total 563
telemt_desync_suppressed_total 1305
telemt_desync_frames_bucket_total{bucket="1_2"} 386
telemt_desync_frames_bucket_total{bucket="3_10"} 840
telemt_desync_frames_bucket_total{bucket="gt_10"} 642
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 14360
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 14048
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 304
telemt_user_connections_total{user="hello"} 638250
telemt_user_connections_current{user="hello"} 434
telemt_user_octets_from_client{user="hello"} 6717032873 (6.26 GB)
telemt_user_octets_to_client{user="hello"} 213826607280 (199.14 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 203675.6 (56h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3520848
telemt_connections_bad_total 38554
telemt_handshake_timeouts_total 231748
telemt_upstream_connect_attempt_total 46099
telemt_upstream_connect_success_total 46078
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 46099
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24303
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21527
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 241
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10651
telemt_me_reconnect_attempts_total 40598
telemt_me_reconnect_success_total 35625
telemt_me_reader_eof_total 37844
telemt_me_idle_close_by_peer_total 37843
telemt_me_route_drop_no_conn_total 1205437
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2936615
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9693
telemt_desync_full_logged_total 3252
telemt_desync_suppressed_total 6441
telemt_desync_frames_bucket_total{bucket="1_2"} 1692
telemt_desync_frames_bucket_total{bucket="3_10"} 3498
telemt_desync_frames_bucket_total{bucket="gt_10"} 4503
telemt_pool_swap_total 193
telemt_me_writer_removed_unexpected_total 36119
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 35584
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 494
telemt_user_connections_total{user="hello"} 2935777
telemt_user_connections_current{user="hello"} 659
telemt_user_octets_from_client{user="hello"} 48412725112 (45.09 GB)
telemt_user_octets_to_client{user="hello"} 1051041732545 (978.86 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 245
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 203678.1 (56h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2354098
telemt_connections_bad_total 23189
telemt_handshake_timeouts_total 275514
telemt_upstream_connect_attempt_total 63556
telemt_upstream_connect_success_total 61068
telemt_upstream_connect_fail_total 2351
telemt_upstream_connect_attempts_per_request{bucket="1"} 63282
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36475
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24427
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2350
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20500
telemt_me_reconnect_attempts_total 52949
telemt_me_reconnect_success_total 43904
telemt_me_reader_eof_total 47079
telemt_me_idle_close_by_peer_total 47072
telemt_me_route_drop_no_conn_total 794756
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1859439
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3895
telemt_desync_full_logged_total 1260
telemt_desync_suppressed_total 2635
telemt_desync_frames_bucket_total{bucket="1_2"} 1052
telemt_desync_frames_bucket_total{bucket="3_10"} 1617
telemt_desync_frames_bucket_total{bucket="gt_10"} 1226
telemt_pool_swap_total 181
telemt_me_writer_removed_unexpected_total 44567
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 43880
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 663
telemt_user_connections_total{user="hello"} 1865472
telemt_user_connections_current{user="hello"} 319
telemt_user_octets_from_client{user="hello"} 28176719867 (26.24 GB)
telemt_user_octets_to_client{user="hello"} 685677808670 (638.59 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 73111.9 (20h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 776510
telemt_connections_bad_total 8071
telemt_handshake_timeouts_total 9105
telemt_upstream_connect_attempt_total 18724
telemt_upstream_connect_success_total 18221
telemt_upstream_connect_fail_total 503
telemt_upstream_connect_attempts_per_request{bucket="1"} 18724
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8652
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9543
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 503
telemt_me_keepalive_timeout_total 1571
telemt_me_reconnect_attempts_total 59865
telemt_me_reconnect_success_total 14560
telemt_me_reader_eof_total 16331
telemt_me_idle_close_by_peer_total 16330
telemt_me_route_drop_no_conn_total 299176
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 725344
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1770
telemt_desync_full_logged_total 566
telemt_desync_suppressed_total 1204
telemt_desync_frames_bucket_total{bucket="1_2"} 526
telemt_desync_frames_bucket_total{bucket="3_10"} 689
telemt_desync_frames_bucket_total{bucket="gt_10"} 555
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 16101
telemt_me_refill_failed_total 1411
telemt_me_writer_restored_same_endpoint_total 14555
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1541
telemt_user_connections_total{user="hello"} 725198
telemt_user_connections_current{user="hello"} 571
telemt_user_octets_from_client{user="hello"} 12886080060 (12.00 GB)
telemt_user_octets_to_client{user="hello"} 243673370976 (226.94 GB)
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 69
```