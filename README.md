# Server Metrics 2026-03-14 10:04:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 187574.5 (52h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5368552
telemt_connections_bad_total 53382
telemt_handshake_timeouts_total 119711
telemt_upstream_connect_attempt_total 39395
telemt_upstream_connect_success_total 39139
telemt_upstream_connect_fail_total 256
telemt_upstream_connect_attempts_per_request{bucket="1"} 39395
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21222
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17763
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 154
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 256
telemt_me_keepalive_timeout_total 7542
telemt_me_reconnect_attempts_total 38689
telemt_me_reconnect_success_total 27472
telemt_me_reader_eof_total 29459
telemt_me_idle_close_by_peer_total 29458
telemt_me_route_drop_no_conn_total 2029939
telemt_me_route_drop_channel_closed_total 29
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4918751
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 18782
telemt_desync_full_logged_total 5135
telemt_desync_suppressed_total 13647
telemt_desync_frames_bucket_total{bucket="1_2"} 4601
telemt_desync_frames_bucket_total{bucket="3_10"} 7176
telemt_desync_frames_bucket_total{bucket="gt_10"} 7005
telemt_pool_swap_total 161
telemt_me_writer_removed_unexpected_total 28224
telemt_me_refill_failed_total 345
telemt_me_writer_restored_same_endpoint_total 27459
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 752
telemt_user_connections_total{user="hello"} 4920194
telemt_user_connections_current{user="hello"} 1634
telemt_user_octets_from_client{user="hello"} 75270014008 (70.10 GB)
telemt_user_octets_to_client{user="hello"} 1568943817485 (1.43 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 469
telemt_user_unique_ips_recent_window{user="hello"} 225
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 87238.5 (24h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 980837
telemt_connections_bad_total 56407
telemt_handshake_timeouts_total 20947
telemt_upstream_connect_attempt_total 22929
telemt_upstream_connect_success_total 22639
telemt_upstream_connect_fail_total 290
telemt_upstream_connect_attempts_per_request{bucket="1"} 22929
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12291
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10055
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 41
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 252
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 290
telemt_me_keepalive_timeout_total 2234
telemt_me_reconnect_attempts_total 26156
telemt_me_reconnect_success_total 16283
telemt_me_reader_eof_total 17462
telemt_me_idle_close_by_peer_total 17461
telemt_me_route_drop_no_conn_total 329058
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 800048
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2245
telemt_desync_full_logged_total 705
telemt_desync_suppressed_total 1540
telemt_desync_frames_bucket_total{bucket="1_2"} 513
telemt_desync_frames_bucket_total{bucket="3_10"} 961
telemt_desync_frames_bucket_total{bucket="gt_10"} 771
telemt_pool_swap_total 72
telemt_me_writer_removed_unexpected_total 16824
telemt_me_refill_failed_total 302
telemt_me_writer_restored_same_endpoint_total 16275
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 541
telemt_user_connections_total{user="hello"} 801943
telemt_user_connections_current{user="hello"} 714
telemt_user_octets_from_client{user="hello"} 8690898605 (8.09 GB)
telemt_user_octets_to_client{user="hello"} 278371449784 (259.25 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 199
telemt_user_unique_ips_recent_window{user="hello"} 112
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 217195.0 (60h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3819534
telemt_connections_bad_total 45051
telemt_handshake_timeouts_total 252396
telemt_upstream_connect_attempt_total 49012
telemt_upstream_connect_success_total 48991
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 49012
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25881
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22853
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 250
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10930
telemt_me_reconnect_attempts_total 42852
telemt_me_reconnect_success_total 37853
telemt_me_reader_eof_total 40187
telemt_me_idle_close_by_peer_total 40186
telemt_me_route_drop_no_conn_total 1311986
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3190898
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10272
telemt_desync_full_logged_total 3492
telemt_desync_suppressed_total 6780
telemt_desync_frames_bucket_total{bucket="1_2"} 1851
telemt_desync_frames_bucket_total{bucket="3_10"} 3718
telemt_desync_frames_bucket_total{bucket="gt_10"} 4703
telemt_pool_swap_total 203
telemt_pool_stale_pick_total 3
telemt_me_writer_removed_unexpected_total 38378
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 37812
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 525
telemt_user_connections_total{user="hello"} 3190063
telemt_user_connections_current{user="hello"} 1001
telemt_user_octets_from_client{user="hello"} 53855564952 (50.16 GB)
telemt_user_octets_to_client{user="hello"} 1143713648681 (1.04 TB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 283
telemt_user_unique_ips_recent_window{user="hello"} 159
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 217197.7 (60h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2521862
telemt_connections_bad_total 23404
telemt_handshake_timeouts_total 318081
telemt_upstream_connect_attempt_total 67261
telemt_upstream_connect_success_total 64758
telemt_upstream_connect_fail_total 2366
telemt_upstream_connect_attempts_per_request{bucket="1"} 66987
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38659
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25933
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2365
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20668
telemt_me_reconnect_attempts_total 58568
telemt_me_reconnect_success_total 46916
telemt_me_reader_eof_total 50275
telemt_me_idle_close_by_peer_total 50267
telemt_me_route_drop_no_conn_total 841893
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1975356
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4043
telemt_desync_full_logged_total 1321
telemt_desync_suppressed_total 2722
telemt_desync_frames_bucket_total{bucket="1_2"} 1138
telemt_desync_frames_bucket_total{bucket="3_10"} 1653
telemt_desync_frames_bucket_total{bucket="gt_10"} 1252
telemt_pool_swap_total 188
telemt_me_writer_removed_unexpected_total 47687
telemt_me_refill_failed_total 355
telemt_me_writer_restored_same_endpoint_total 46892
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 771
telemt_user_connections_total{user="hello"} 1981547
telemt_user_connections_current{user="hello"} 420
telemt_user_octets_from_client{user="hello"} 29568213339 (27.54 GB)
telemt_user_octets_to_client{user="hello"} 715128552846 (666.02 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 86631.1 (24h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 966222
telemt_connections_bad_total 15329
telemt_handshake_timeouts_total 12656
telemt_upstream_connect_attempt_total 21897
telemt_upstream_connect_success_total 21310
telemt_upstream_connect_fail_total 587
telemt_upstream_connect_attempts_per_request{bucket="1"} 21897
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10166
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11118
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 587
telemt_me_keepalive_timeout_total 1683
telemt_me_reconnect_attempts_total 72411
telemt_me_reconnect_success_total 16975
telemt_me_reader_eof_total 19118
telemt_me_idle_close_by_peer_total 19117
telemt_me_route_drop_no_conn_total 369329
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 895383
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2365
telemt_desync_full_logged_total 740
telemt_desync_suppressed_total 1625
telemt_desync_frames_bucket_total{bucket="1_2"} 803
telemt_desync_frames_bucket_total{bucket="3_10"} 877
telemt_desync_frames_bucket_total{bucket="gt_10"} 685
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 18865
telemt_me_refill_failed_total 1727
telemt_me_writer_restored_same_endpoint_total 16970
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1890
telemt_user_connections_total{user="hello"} 895327
telemt_user_connections_current{user="hello"} 695
telemt_user_octets_from_client{user="hello"} 15843295736 (14.76 GB)
telemt_user_octets_to_client{user="hello"} 299935521948 (279.34 GB)
telemt_user_unique_ips_current{user="hello"} 190
telemt_user_unique_ips_recent_window{user="hello"} 87
```