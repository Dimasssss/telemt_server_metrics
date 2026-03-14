# Server Metrics 2026-03-14 10:15:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 188188.0 (52h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5392886
telemt_connections_bad_total 55102
telemt_handshake_timeouts_total 119976
telemt_upstream_connect_attempt_total 39555
telemt_upstream_connect_success_total 39299
telemt_upstream_connect_fail_total 256
telemt_upstream_connect_attempts_per_request{bucket="1"} 39555
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21302
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17842
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 155
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 256
telemt_me_keepalive_timeout_total 7588
telemt_me_reconnect_attempts_total 38818
telemt_me_reconnect_success_total 27601
telemt_me_reader_eof_total 29589
telemt_me_idle_close_by_peer_total 29588
telemt_me_route_drop_no_conn_total 2038914
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4940715
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 18849
telemt_desync_full_logged_total 5157
telemt_desync_suppressed_total 13692
telemt_desync_frames_bucket_total{bucket="1_2"} 4630
telemt_desync_frames_bucket_total{bucket="3_10"} 7191
telemt_desync_frames_bucket_total{bucket="gt_10"} 7028
telemt_pool_swap_total 161
telemt_me_writer_removed_unexpected_total 28354
telemt_me_refill_failed_total 345
telemt_me_writer_restored_same_endpoint_total 27588
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 753
telemt_user_connections_total{user="hello"} 4942159
telemt_user_connections_current{user="hello"} 1706
telemt_user_octets_from_client{user="hello"} 75771959564 (70.57 GB)
telemt_user_octets_to_client{user="hello"} 1574595705345 (1.43 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 470
telemt_user_unique_ips_recent_window{user="hello"} 251
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 87852.1 (24h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 989777
telemt_connections_bad_total 56890
telemt_handshake_timeouts_total 21241
telemt_upstream_connect_attempt_total 23077
telemt_upstream_connect_success_total 22786
telemt_upstream_connect_fail_total 291
telemt_upstream_connect_attempts_per_request{bucket="1"} 23077
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12368
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10124
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 42
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 252
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 291
telemt_me_keepalive_timeout_total 2254
telemt_me_reconnect_attempts_total 26259
telemt_me_reconnect_success_total 16384
telemt_me_reader_eof_total 17573
telemt_me_idle_close_by_peer_total 17572
telemt_me_route_drop_no_conn_total 332184
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 807973
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2272
telemt_desync_full_logged_total 711
telemt_desync_suppressed_total 1561
telemt_desync_frames_bucket_total{bucket="1_2"} 523
telemt_desync_frames_bucket_total{bucket="3_10"} 970
telemt_desync_frames_bucket_total{bucket="gt_10"} 779
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 16927
telemt_me_refill_failed_total 302
telemt_me_writer_restored_same_endpoint_total 16376
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 543
telemt_user_connections_total{user="hello"} 809863
telemt_user_connections_current{user="hello"} 565
telemt_user_octets_from_client{user="hello"} 8797018145 (8.19 GB)
telemt_user_octets_to_client{user="hello"} 281893193540 (262.53 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 191
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 217808.7 (60h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3836001
telemt_connections_bad_total 45728
telemt_handshake_timeouts_total 253540
telemt_upstream_connect_attempt_total 49113
telemt_upstream_connect_success_total 49092
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 49113
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25930
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22905
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 250
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 11002
telemt_me_reconnect_attempts_total 42953
telemt_me_reconnect_success_total 37954
telemt_me_reader_eof_total 40291
telemt_me_idle_close_by_peer_total 40290
telemt_me_route_drop_no_conn_total 1317212
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3204939
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10302
telemt_desync_full_logged_total 3503
telemt_desync_suppressed_total 6799
telemt_desync_frames_bucket_total{bucket="1_2"} 1864
telemt_desync_frames_bucket_total{bucket="3_10"} 3727
telemt_desync_frames_bucket_total{bucket="gt_10"} 4711
telemt_pool_swap_total 203
telemt_pool_stale_pick_total 3
telemt_me_writer_removed_unexpected_total 38482
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 37913
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 528
telemt_user_connections_total{user="hello"} 3204094
telemt_user_connections_current{user="hello"} 1017
telemt_user_octets_from_client{user="hello"} 54357553380 (50.62 GB)
telemt_user_octets_to_client{user="hello"} 1149924539821 (1.05 TB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 291
telemt_user_unique_ips_recent_window{user="hello"} 176
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 217811.2 (60h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2530237
telemt_connections_bad_total 23404
telemt_handshake_timeouts_total 319810
telemt_upstream_connect_attempt_total 67471
telemt_upstream_connect_success_total 64968
telemt_upstream_connect_fail_total 2366
telemt_upstream_connect_attempts_per_request{bucket="1"} 67197
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38787
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26015
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2365
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20726
telemt_me_reconnect_attempts_total 58778
telemt_me_reconnect_success_total 47126
telemt_me_reader_eof_total 50485
telemt_me_idle_close_by_peer_total 50477
telemt_me_route_drop_no_conn_total 844048
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1981505
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4044
telemt_desync_full_logged_total 1322
telemt_desync_suppressed_total 2722
telemt_desync_frames_bucket_total{bucket="1_2"} 1139
telemt_desync_frames_bucket_total{bucket="3_10"} 1653
telemt_desync_frames_bucket_total{bucket="gt_10"} 1252
telemt_pool_swap_total 188
telemt_me_writer_removed_unexpected_total 47897
telemt_me_refill_failed_total 355
telemt_me_writer_restored_same_endpoint_total 47102
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 771
telemt_user_connections_total{user="hello"} 1987704
telemt_user_connections_current{user="hello"} 484
telemt_user_octets_from_client{user="hello"} 29657941419 (27.62 GB)
telemt_user_octets_to_client{user="hello"} 716843522314 (667.61 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 148
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 87245.0 (24h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 976288
telemt_connections_bad_total 15801
telemt_handshake_timeouts_total 12840
telemt_upstream_connect_attempt_total 21965
telemt_upstream_connect_success_total 21378
telemt_upstream_connect_fail_total 587
telemt_upstream_connect_attempts_per_request{bucket="1"} 21965
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10201
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11151
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 587
telemt_me_keepalive_timeout_total 1695
telemt_me_reconnect_attempts_total 72479
telemt_me_reconnect_success_total 17041
telemt_me_reader_eof_total 19185
telemt_me_idle_close_by_peer_total 19184
telemt_me_route_drop_no_conn_total 374106
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 904156
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2408
telemt_desync_full_logged_total 751
telemt_desync_suppressed_total 1657
telemt_desync_frames_bucket_total{bucket="1_2"} 816
telemt_desync_frames_bucket_total{bucket="3_10"} 891
telemt_desync_frames_bucket_total{bucket="gt_10"} 701
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 18932
telemt_me_refill_failed_total 1727
telemt_me_writer_restored_same_endpoint_total 17036
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1891
telemt_user_connections_total{user="hello"} 904098
telemt_user_connections_current{user="hello"} 730
telemt_user_octets_from_client{user="hello"} 15979172044 (14.88 GB)
telemt_user_octets_to_client{user="hello"} 303932427928 (283.06 GB)
telemt_user_unique_ips_current{user="hello"} 212
telemt_user_unique_ips_recent_window{user="hello"} 114
```