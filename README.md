# Server Metrics 2026-03-14 04:32:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 167611.7 (46h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4767396
telemt_connections_bad_total 39896
telemt_handshake_timeouts_total 109831
telemt_upstream_connect_attempt_total 35383
telemt_upstream_connect_success_total 35151
telemt_upstream_connect_fail_total 232
telemt_upstream_connect_attempts_per_request{bucket="1"} 35383
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19159
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15845
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 147
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 232
telemt_me_keepalive_timeout_total 7297
telemt_me_reconnect_attempts_total 34604
telemt_me_reconnect_success_total 24461
telemt_me_reader_eof_total 26257
telemt_me_idle_close_by_peer_total 26256
telemt_me_route_drop_no_conn_total 1807148
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4373069
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16894
telemt_desync_full_logged_total 4559
telemt_desync_suppressed_total 12335
telemt_desync_frames_bucket_total{bucket="1_2"} 4215
telemt_desync_frames_bucket_total{bucket="3_10"} 6452
telemt_desync_frames_bucket_total{bucket="gt_10"} 6227
telemt_pool_swap_total 146
telemt_me_writer_removed_unexpected_total 25126
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 24448
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 665
telemt_user_connections_total{user="hello"} 4374642
telemt_user_connections_current{user="hello"} 968
telemt_user_octets_from_client{user="hello"} 64024614264 (59.63 GB)
telemt_user_octets_to_client{user="hello"} 1379298685577 (1.25 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 303
telemt_user_unique_ips_recent_window{user="hello"} 124
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 67275.4 (18h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 737872
telemt_connections_bad_total 52681
telemt_handshake_timeouts_total 13477
telemt_upstream_connect_attempt_total 18536
telemt_upstream_connect_success_total 18276
telemt_upstream_connect_fail_total 260
telemt_upstream_connect_attempts_per_request{bucket="1"} 18536
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10130
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7895
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 221
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 260
telemt_me_keepalive_timeout_total 2099
telemt_me_reconnect_attempts_total 16353
telemt_me_reconnect_success_total 12900
telemt_me_reader_eof_total 13699
telemt_me_idle_close_by_peer_total 13698
telemt_me_route_drop_no_conn_total 245362
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 588610
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1765
telemt_desync_full_logged_total 515
telemt_desync_suppressed_total 1250
telemt_desync_frames_bucket_total{bucket="1_2"} 371
telemt_desync_frames_bucket_total{bucket="3_10"} 781
telemt_desync_frames_bucket_total{bucket="gt_10"} 613
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 13185
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 12892
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 285
telemt_user_connections_total{user="hello"} 590561
telemt_user_connections_current{user="hello"} 251
telemt_user_octets_from_client{user="hello"} 6311912449 (5.88 GB)
telemt_user_octets_to_client{user="hello"} 196751764696 (183.24 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 108
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 197232.2 (54h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3434006
telemt_connections_bad_total 37020
telemt_handshake_timeouts_total 226573
telemt_upstream_connect_attempt_total 44609
telemt_upstream_connect_success_total 44588
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 44609
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23466
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20878
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 237
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10604
telemt_me_reconnect_attempts_total 39415
telemt_me_reconnect_success_total 34446
telemt_me_reader_eof_total 36592
telemt_me_idle_close_by_peer_total 36591
telemt_me_route_drop_no_conn_total 1173921
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2860857
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9451
telemt_desync_full_logged_total 3167
telemt_desync_suppressed_total 6284
telemt_desync_frames_bucket_total{bucket="1_2"} 1640
telemt_desync_frames_bucket_total{bucket="3_10"} 3409
telemt_desync_frames_bucket_total{bucket="gt_10"} 4402
telemt_pool_swap_total 187
telemt_me_writer_removed_unexpected_total 34925
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 34405
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 479
telemt_user_connections_total{user="hello"} 2860071
telemt_user_connections_current{user="hello"} 460
telemt_user_octets_from_client{user="hello"} 45687230480 (42.55 GB)
telemt_user_octets_to_client{user="hello"} 1024491169285 (954.13 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 172
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 197234.9 (54h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2302268
telemt_connections_bad_total 23064
telemt_handshake_timeouts_total 258384
telemt_upstream_connect_attempt_total 61675
telemt_upstream_connect_success_total 59202
telemt_upstream_connect_fail_total 2336
telemt_upstream_connect_attempts_per_request{bucket="1"} 61401
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35372
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23664
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2335
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20458
telemt_me_reconnect_attempts_total 51387
telemt_me_reconnect_success_total 42349
telemt_me_reader_eof_total 45419
telemt_me_idle_close_by_peer_total 45412
telemt_me_route_drop_no_conn_total 781718
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1827401
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3877
telemt_desync_full_logged_total 1247
telemt_desync_suppressed_total 2630
telemt_desync_frames_bucket_total{bucket="1_2"} 1044
telemt_desync_frames_bucket_total{bucket="3_10"} 1610
telemt_desync_frames_bucket_total{bucket="gt_10"} 1223
telemt_pool_swap_total 175
telemt_me_writer_removed_unexpected_total 42997
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 42325
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 648
telemt_user_connections_total{user="hello"} 1833352
telemt_user_connections_current{user="hello"} 249
telemt_user_octets_from_client{user="hello"} 27772367555 (25.87 GB)
telemt_user_octets_to_client{user="hello"} 673989094306 (627.70 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 98
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 66668.1 (18h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 730828
telemt_connections_bad_total 7975
telemt_handshake_timeouts_total 8742
telemt_upstream_connect_attempt_total 17197
telemt_upstream_connect_success_total 16740
telemt_upstream_connect_fail_total 457
telemt_upstream_connect_attempts_per_request{bucket="1"} 17197
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7914
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8800
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 457
telemt_me_keepalive_timeout_total 1534
telemt_me_reconnect_attempts_total 52167
telemt_me_reconnect_success_total 13407
telemt_me_reader_eof_total 14954
telemt_me_idle_close_by_peer_total 14953
telemt_me_route_drop_no_conn_total 279107
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 682010
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1721
telemt_desync_full_logged_total 540
telemt_desync_suppressed_total 1181
telemt_desync_frames_bucket_total{bucket="1_2"} 513
telemt_desync_frames_bucket_total{bucket="3_10"} 669
telemt_desync_frames_bucket_total{bucket="gt_10"} 539
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 14732
telemt_me_refill_failed_total 1207
telemt_me_writer_restored_same_endpoint_total 13402
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1325
telemt_user_connections_total{user="hello"} 681882
telemt_user_connections_current{user="hello"} 332
telemt_user_octets_from_client{user="hello"} 12368733900 (11.52 GB)
telemt_user_octets_to_client{user="hello"} 220181449964 (205.06 GB)
telemt_user_unique_ips_current{user="hello"} 127
telemt_user_unique_ips_recent_window{user="hello"} 50
```